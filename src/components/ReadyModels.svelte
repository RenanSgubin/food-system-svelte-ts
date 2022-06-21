

<section class="ready-models-container">
    <div class="ready-models-content">
        <div class="line"></div>
        <span>1</span>
        <span>2</span>
        <span>3</span>
        <span>4</span>
        <span>5</span>
        <span>6</span>
        <span>7</span>
        <span>8</span>
        <span>9</span>
    </div>
</section>


<style>

    :root {
        --span-width: 90px;
    }

    .ready-models-container {
        height: 12vh;
        display: flex;
        justify-content: center;
        align-items: center;
        font-family: 'Poppins', sans-serif;
        font-size: 1.2rem;
    }

    .ready-models-content {
        position: relative;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .ready-models-content span {
        width: var(--span-width);
        height: var(--span-width);
        border-radius: 50%;
        background-color: aliceblue;
        z-index: 5;
        display: flex;
        justify-content: center;
        align-items: center;
        border: 1px solid rgb(220, 220, 220);
        margin: 7px;
        z-index: 7;
    }

    .line {
        position: absolute;
        width: calc(9 * var(--span-width));
        height: 2px;
        background-color: rgb(220, 220, 220);
        top: 50%;
        transform: translateY(-50%);
        z-index: 6;
    }

</style>