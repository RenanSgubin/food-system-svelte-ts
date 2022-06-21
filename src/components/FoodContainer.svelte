
<script>
    import Food from "./Food.svelte";
    import ReadyModels from "./ReadyModels.svelte";
    import TitleFoodContainer from "./TitleFoodContainer.svelte"; 
</script>

<section class="food-container">
    <div class="food-content">
        <TitleFoodContainer/>
        <ReadyModels/>
        <Food/>
    </div>
</section>

<style>

    .food-container {
        width: 82%;
        height: 100vh;
        display: flex;
        justify-content: center;
        align-items: center;
        background-color: rgb(231, 231, 231);
    }

    .food-content {
        width: 100%;
        height: 100vh;
    }

</style>