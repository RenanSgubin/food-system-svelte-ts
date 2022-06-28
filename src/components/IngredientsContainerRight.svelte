
<script>

</script>

<section class="ingredientes-container">
    <span class="ingredients-identifier">
        <img src="/images/chevrons-down.svg" alt="">
    </span>
    <div class="ingredients-content">
        <div class="ingredients-content-overflow">
            <span id="first-ingredient">0</span>
            <span>1</span>
            <span>2</span>
            <span>3</span>
            <span id="last-ingredient">4</span>
        </div>
    </div>
</section>

<style>

    .ingredientes-container {
        position: absolute;
        right: 0%;
        width: 9%;
        height: 100vh;
        display: flex;
        justify-content: center;
        align-items: center;
        background-color: #fb9179;
        z-index: 5;
        overflow: hidden;
        border-left: 2px solid rgb(28, 28, 29);
    }

    .ingredients-identifier {
        position: absolute;
        top: 0%;
        width: 100%;
        height: 8vh;
        background-color: #2b2c30;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .ingredients-identifier img {
        width: 40px;
    }

    .ingredients-content {
        position: relative;
        width: 100%;
        height: 95vh;
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
    }

    .ingredients-content-overflow {
        position: absolute;
        top: 0%;
        width: 100%;
        height: 100%;
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
    }

    .ingredients-content-overflow span {
        width: 95px;
        height: 95px;
        border-radius: 50%;
        background-color: #f58369;
        display: flex;
        justify-content: center;
        align-items: center;
        margin: 9px;
        border: 2px solid #fa7d61;
    }

</style>