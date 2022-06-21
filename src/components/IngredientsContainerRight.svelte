
<script>

</script>

<section class="ingredientes-container">
    <div class="ingredients-content">
        <div class="ingredients-content-overflow">
            <span id="first-ingredient">0</span>
            <span>1</span>
            <span>2</span>
            <span>3</span>
            <span>4</span>
            <span id="last-ingredient">5</span>
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
        background-color: rgb(242, 241, 241);
        z-index: 5;
        overflow: hidden;
        border-left: 2px solid rgb(214, 214, 214);
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
        background-color: aliceblue;
        display: flex;
        justify-content: center;
        align-items: center;
        border: 1px solid rgb(220, 220, 220);
        margin: 9px;
    }

</style>