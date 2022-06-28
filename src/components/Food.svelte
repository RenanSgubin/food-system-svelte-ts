

<section class="food">
    <section class="food-content">
        <span class="hamburguer-bread-top">
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
        <span class="bacon">
            <div class="bacon-line"></div>
            <div class="bacon-line"></div>
            <div class="bacon-line"></div>
        </span>
        <span class="cheese"></span>
        <span class="meat"></span>
        <span class="picle">
            <div></div>
            <div></div>
        </span>
        <span class="tomatoes">
            <div></div>
            <div></div>
            <div></div>
        </span>
        <span class="lettuce"></span>
        <span class="egg"></span>
        <span class="hamburguer-bread-bottom"></span>
    </section>

    <article class="food-floor"></article>

</section>

<style>

    :root {
        --food-width: 600px;
    }

    .food {
        position: relative;
        width: 100%;
        height: 80vh;
        display: flex;
        justify-content: end;
        align-items: center;
        flex-direction: column;
        background-image: linear-gradient(120deg, #fdfbfb 0%, #ebedee 100%);
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

    .hamburguer-bread-top {
        border-top-left-radius: 290px;
        border-top-right-radius: 290px;
        height: 210px;
    }   

    .hamburguer-bread-bottom {
        border-bottom-left-radius: 100px;
        border-bottom-right-radius: 100px;
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
        left: 30%;
        top: 20%;
    }

    .sesame:nth-child(3) {
        left: 40%;
        top: 70%;
    }

    .sesame:nth-child(4) {
        left: 50%;
        top: 20%;
    }

    .sesame:nth-child(5) {
        left: 60%;
        top: 70%;
    }

    .sesame:nth-child(6) {
        left: 70%;
        top: 20%;
    }

    .sesame:nth-child(7) {
        left: 80%;
        top: 70%;
    }

    .bacon {
        width: calc(var(--food-width) + 70px);
        height: 21px;
        background-color: #b41f1f;
        display: flex;
        align-items: center;
        flex-direction: column;
    }

    .bacon-line {
        width: 100%;
        height: 4px;
        background-color: #971515;
    }

    .cheese {
        width: var(--food-width);
        height: 20px;
        background-color: rgb(223, 206, 21);
        border-radius: 5px;
    }

    .meat {
        width: var(--food-width);
        height: 60px;
        background-color: rgb(62, 33, 33);
        border-radius: 20px;
    }

    .tomatoes, .picle {
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .tomatoes div {
        width: calc( var(--food-width) / 3);
        height: 20px;
        background-color: rgb(237, 64, 64);
        border-radius: 5px;
    }

    .picle div {
        width: calc( var(--food-width) / 2);
        height: 20px;
        background-color: rgb(40, 136, 10);
        border-radius: 5px;
    }

    .lettuce {
        width: var(--food-width);
        height: 20px;
        background-color: rgb(80, 196, 38);  
    }

    .egg {
        width: var(--food-width);
        height: 20px;
        background: rgb(254,254,254);
        background: linear-gradient(90deg, rgba(254,254,254,1) 47%, rgba(244,237,15,1) 47%); 
    }

    /*Floor*/
    .food-floor {
        width: 100%;
        height: 12vh;
        background-color: rgb(41, 41, 41);
        z-index: 2;
    }

</style>