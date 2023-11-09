<script setup>

</script>

<template>
<div class="wrapper"><div class="main_container">
        <div class="container_one">
            <div class="profile">
                <img src="./icons/svalereden_v0.jpg" alt="Svalereden">
                <h2>Svalereden</h2>
                <h3>tatovør</h3>
            </div>
            <div class="socials">
                    <div class="link">
                        <img src="" alt="">
                        <a href="">
                            <img src="" alt="">
                            <h2>Instagram</h2>
                        </a>
                    </div>
                    <div class="link">
                        <a href="https://www.facebook.com/profile.php?id=100085872138502&sk=photos">
                            <img src="" alt="">
                            <h2>Facebook</h2>
                        </a>
                    </div>
            </div>
        </div>
        <div class="container_two">
            <div class="about_us">
                <h1>Om os</h1>
                <p>Vi er en tatovør biks bestående af 3 tatovøer placeret i Rudkøbing, Langeland</p>
            </div>
            <div class="art_style">
                <h1>Stilarter</h1>
                <p>De stilarter vi tatovøer i er danske old school tattoveringer og klassisk feminin </p>
            </div>
            <div class="button_container">
                <div class="examples_button">
                    <a href="">Old School Tattoveringer</a>
                <div class="examples_button">
                        <a href="">Feminine Tattoveringer</a>
                </div>
                </div>
            </div>
        </div>
    </div></div>
    
</template>

<style>

    .wrapper{
        display: flex;
        justify-content: center;
    }

    img{
        height: 20px;
    }

    .main_container{
        display: flex;
        flex-direction: row;
        background-color: aquamarine;
        border-radius: 25px;
        width: 60%;
    }

    .container_one{
        background-color: rgb(255, 69, 1);
        padding: 2.5%;
        width: 20%;
        border-top-left-radius: 25px;
        border-bottom-left-radius: 25px;
    }

    .profile img{
        height: 10rem;
        border-radius: 50%;
    }

    .link a{
        text-decoration: none;
        color: black;
    }

    .link img{
        height: 2rem;
    }

    .container_two{
        background-color: rgb(237, 241, 20);
        margin: 2.5%;
        width: 80%;
        border-radius: 25px;
    }

    .about_us{
        text-align: left;
    }

    .button_container{
        display: flex;
        flex-direction: row;
        justify-content: center;
        align-items: center;
    }

    .examples_button{
        background-color: rgb(255, 255, 255);
        margin: 10px;
        padding: 5px;
    }

    .examples_button a{
        text-decoration: none;
        color: rgb(16, 65, 201);
    }
</style>