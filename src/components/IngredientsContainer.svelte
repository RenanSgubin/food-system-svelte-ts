
<script lang="ts"></script>

<section class="ingredientes-container">
    <a href="#last-ingredient" class="to-last-first-ingredient">
        <svg
            xmlns="http://www.w3.org/2000/svg"
            width="24"
            height="24"
            viewBox="0 0 24 24"
            fill="none"
            stroke="currentColor"
            stroke-width="2"
            stroke-linecap="round"
            stroke-linejoin="round"
            >
            <line x1="12" y1="19" x2="12" y2="5" />
            <polyline points="5 12 12 5 19 12" />
        </svg>
    </a>
    <div class="ingredients-content">
        <div class="ingredients-content-overflow">
            <span id="first-ingredient">1</span>
            <span>1</span>
            <span>1</span>
            <span>1</span>
            <span>1</span>
            <span>1</span>
            <span>1</span>
            <span>1</span>
            <span>1</span>
            <span>1</span>
            <span>1</span>
            <span id="last-ingredient">1</span>
        </div>
    </div>
    <a href="#last-ingredient" class="to-last-first-ingredient">
        <svg
            xmlns="http://www.w3.org/2000/svg"
            width="24"
            height="24"
            viewBox="0 0 24 24"
            fill="none"
            stroke="currentColor"
            stroke-width="2"
            stroke-linecap="round"
            stroke-linejoin="round"
            >
            <line x1="12" y1="19" x2="12" y2="5" />
            <polyline points="5 12 12 5 19 12" />
        </svg>
    </a>
</section>

<style>

    .ingredientes-container {
        position: relative;
        width: 17%;
        height: 100vh;
        display: flex;
        justify-content: center;
        align-items: center;
        background-color: rgb(242, 241, 241);
        overflow: hidden;
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
        width: 150px;
        height: 150px;
        border-radius: 50%;
        background-color: aliceblue;
        display: flex;
        justify-content: center;
        align-items: center;
        border: 1px solid rgb(220, 220, 220);
        margin: 10px;
    }

    .to-last-first-ingredient {
        position: absolute;
        left: -30px;
        z-index: 5;
        width: 70px;
        height: 70px;
        border-radius: 50%;
        background-color: rgb(126, 179, 226);
    }

    .to-last-first-ingredient:nth-child(1) {
        top: -25px;
    }

    .to-last-first-ingredient:nth-child(3) {
        bottom: -25px;
    }

    .to-last-first-ingredient svg {
        z-index: 9999;
    }

</style>