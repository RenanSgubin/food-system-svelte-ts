
<script>

    import IngredientsContainerRight from "../components/IngredientsContainerRight.svelte";
    import FoodContainer from "../components/FoodContainer.svelte";
    import IngredientsContainer from "../components/IngredientsContainer.svelte";

</script>

<svelte:head>
    <link href="https://fonts.googleapis.com/css2?family=Nunito&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@600&display=swap" rel="stylesheet">
</svelte:head>

<section class="app-container">
    <IngredientsContainer/>
    <FoodContainer/>
    <IngredientsContainerRight/>
</section>

<style>

    .app-container {
        position: relative;
        width: 100%;
        height: 100vh;
        background-color: aliceblue;
        display: flex;
        font-family: 'Nunito', sans-serif;
        scroll-behavior: smooth;
    }

</style>