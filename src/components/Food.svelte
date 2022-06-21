

<section class="food">
    <img src="/images/restaurant-background.jpg" alt="restauraunt-background" class="restauraunt-bg">
    <section class="food-content">
        <span class="hamburguer-bread-top">
            <div class="sesame"></div>
            <div class="sesame"></div>
            <div class="sesame"></div>
            <div class="sesame"></div>
            <div class="sesame"></div>
            <div class="sesame"></div>
            <div class="sesame"></div>
            <div class="sesame"></div>
            <div class="sesame"></div>
        </span>
        <span class="cheese"></span>
        <span class="meat"></span>
        <span class="tomatoes">
            <span></span>
            <span></span>
            <span></span>
        </span>
        <span class="lettuce"></span>
        <span class="hamburguer-bread-bottom"></span>
    </section>

    <article class="food-floor">

    </article>

</section>

<style>

    :root {
        --food-width: 700px;
    }

    .food {
        position: relative;
        width: 100%;
        height: 80vh;
        display: flex;
        justify-content: end;
        align-items: center;
        flex-direction: column;
    }

    .restauraunt-bg {
        position: absolute;
        top: -12vh;
        width: 100%;
        -webkit-filter: blur(15px);
        -moz-filter: blur(15px);
        -o-filter: blur(15px);
        -ms-filter: blur(15px);
        filter: brightness(20%);
    }

    .food-content {
        position: relative;
        width: 90%;
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
        margin-bottom: 20px;
    }

    .hamburguer-bread-top, .hamburguer-bread-bottom {
        position: relative;
        width: var(--food-width);
        height: 130px;
        background-color: rgb(228, 184, 81);
        border: 5px solid rgb(109, 84, 22);
    }

    .sesame {
        position: absolute;
        width: 40px;
        height: 15px;
        background-color: rgb(227, 197, 126);
        border-radius: 60%;
        left: 10%;
        top: 20%;
    }

    .sesame:nth-child(1) {
        left: 15%;
        top: 70%;
    }

    .sesame:nth-child(2) {
        left: 25%;
        top: 20%;
    }

    .sesame:nth-child(3) {
        left: 35%;
        top: 50%;
    }

    .sesame:nth-child(4) {
        left: 45%;
        top: 20%;
    }

    .sesame:nth-child(5) {
        left: 55%;
        top: 70%;
    }

    .sesame:nth-child(6) {
        left: 65%;
        top: 30%;
    }

    .sesame:nth-child(7) {
        left: 75%;
        top: 70%;
    }

    .sesame:nth-child(8) {
        left: 85%;
        top: 25%;
    }


    .hamburguer-bread-top {
        border-top-left-radius: 200px;
        border-top-right-radius: 200px;
    }   

    .hamburguer-bread-bottom {
        border-bottom-left-radius: 200px;
        border-bottom-right-radius: 200px;
    }

    .cheese {
        width: var(--food-width);
        height: 20px;
        background-color: rgb(223, 206, 21);
        border-radius: 20px;
    }

    .meat {
        width: var(--food-width);
        height: 70px;
        background-color: rgb(62, 33, 33);
        border-radius: 200px;
    }

    .tomatoes {
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .tomatoes span {
        width: calc( var(--food-width) / 3);
        height: 20px;
        background-color: rgb(237, 64, 64);
        border-radius: 200px;
    }

    .lettuce {
        width: var(--food-width);
        height: 20px;
        background-color: rgb(80, 196, 38);  
    }

    /*Floor*/
    .food-floor {
        width: 100%;
        height: 17vh;
        background-color: rgb(41, 41, 41);
        z-index: 2;
    }

</style>