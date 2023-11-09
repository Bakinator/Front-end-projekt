<script setup>
import jsonData from "../../examples.json"
const examplesData = jsonData
</script>

<template>
  <div class="main_example_cards_container">
    <div class="example_cards" v-for="(item, index) in examplesData.ExamplesArray" :key="index">
      <h2>{{ item.Title }}</h2>
      <img :src="item.Image" alt="">
      <p>{{ item.About }}</p>
      <div class="links">
        <a href="https://www.facebook.com/profile.php?id=100085872138502&sk=photos"><img src="" alt="Facebook"></a>
      </div>
    </div>
  </div>
</template>

<style>
    .main_example_cards_container{
        display: flex;
        justify-content: center;
        align-items: center;
        flex-wrap: wrap;
    }

    .example_cards{
        margin: 10px;
        padding: 10px;
        flex-wrap: 0 0 40%;
        background-color: white;
        border-radius: 25px;
        box-shadow: rgba(0, 0, 0, 0.24) 0px 3px 8px;
    }

    .example_cards img{
        height: 20rem;
    }
</style>