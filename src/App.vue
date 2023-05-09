<script setup>
import { RouterLink, RouterView } from "vue-router";
import TodoHeader from "./components/TodoHeader.vue";
</script>

<template>
  <TodoHeader />
  <RouterView />
</template>
<style>
@import url("https://fonts.googleapis.com/css2?family=Cabin:ital,wght@0,400;0,500;0,700;1,400&display=swap");
* {
  font-family: "Cabin", sans-serif;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.container {
  max-width: 1100px;
  margin: 0 auto;
}
</style>
