<template>
  <div class="recipe container">
    <Recipe v-bind:name="$route.params.id" />
  </div>
</template>

<script>
import Recipe from "@/components/Recipe.vue";
export default {
  name: "recipe",
  components: {
    Recipe
  }
};
</script>

<style>
.container.mb-4.mb-4 {
  display: none;
}
footer.container {
  display: none;
}
.print-button {
  display: none;
}
</style>
