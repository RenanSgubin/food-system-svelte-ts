
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
            <span>5</span>
            <span>6</span>
            <span>7</span>
            <span>8</span>
            <span>9</span>
            <span>10</span>
            <span id="last-ingredient">11</span>
        </div>
    </div>
</section>

<style>

    .ingredientes-container {
        position: relative;
        width: 9%;
        height: 100vh;
        display: flex;
        justify-content: center;
        align-items: center;
        background-color: rgb(242, 241, 241);
        z-index: 5;
        overflow: hidden;
        border-right: 2px solid rgb(214, 214, 214);
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
        height: auto;
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