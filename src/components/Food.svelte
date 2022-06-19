

<section class="food">
    <section class="food-content">
        <span class="hamburguer-bread-top"></span>
        <span class="cheese"></span>
        <span class="meat"></span>
        <span class="tomatoes">
            <span></span>
            <span></span>
            <span></span>
        </span>
        <span></span>
        <span class="hamburguer-bread-bottom"></span>
    </section>
</section>

<style>

    :root {
        --food-width: 800px;
    }

    .food {
        width: 100%;
        height: 80vh;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .food-content {
        width: 90%;
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
    }

    .hamburguer-bread-top, .hamburguer-bread-bottom {
        width: var(--food-width);
        height: 160px;
        background-color: rgb(228, 184, 81);
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
        height: 100px;
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
        
    }

</style>