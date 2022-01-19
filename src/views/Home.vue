<template>
  <div class="home">
    <h1>My Recipes</h1>
    <button>Add new Recipe</button>

    <div class="recipes"></div>
    <!-- RECIPE TO GO HERE -->

    <div class="add-recipe-popup">
      <div class="popup-content">
        <h2>Add new recipe</h2>

        <form @submit.prevent="">
          <div class="group">
            <label>Title</label>
            <input type="text" />
          </div>

          <div class="group">
            <label>Description</label>
            <textarea></textarea>
          </div>

          <div class="group">
            <label>Ingredients</label>
            <div class="ingredient">
              <input type="text" />
            </div>
            <button type="button">Add Ingredient</button>
          </div>

          <div class="group">
            <label>Method</label>
            <div class="method">
              <textarea></textarea>
            </div>
            <button type="button">Add step</button>
          </div>
        </form>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Home",
};
</script>
