<script setup lang="ts">
import AppHeader from "./components/AppHeader.vue";
import TodoList from "./components/TodoList.vue";
</script>

<template>
  <AppHeader />

  <TodoList />
</template>

<style scoped>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f4f4f4;
}
header {
  background-color: #4caf50;
  color: white;
  padding: 10px 0;
  text-align: center;
}
</style>