
<script>

    import FoodContainer from "../components/FoodContainer.svelte";
    import IngredientsContainer from "../components/IngredientsContainer.svelte";

</script>

<svelte:head>
    <link href="https://fonts.googleapis.com/css2?family=Nunito&display=swap" rel="stylesheet">
</svelte:head>

<section class="app-container">
    <IngredientsContainer/>
    <FoodContainer/>
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
</section>

<style>

    .app-container {
        position: relative;
        width: 100%;
        height: 100vh;
        background-color: aliceblue;
        display: flex;
        font-family: 'Nunito', sans-serif;
    }

</style>