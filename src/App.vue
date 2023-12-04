<script setup>
import TodoHeader from "./components/TodoHeader.vue";
import TodosView from "./views/TodosView.vue";
</script>

<template>
  <TodoHeader />
  <TodosView />
</template>

<style lang="scss">
@import url("https://fonts.googleapis.com/css2?family=Lato&display=swap");

* {
  font-family: "Lato", sans-serif;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.container {
  max-width: 1100px;
  margin: 0 auto;
}
</style>