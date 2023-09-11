<script setup>
// Vue js code here

import { RouterView } from "vue-router";
</script>

<template>
  <div>
    <div>This is projects Page!</div>
    <h1>{{ $route.params.id }}</h1>
    <RouterView />
  </div>

  <!-- html codes -->
</template>

<style scoped>
/* Any css  */

.about {
  border: 5px outset rebeccapurple;
  background-color: aquamarine;
  text-align: center;
  height: 300px;
}
</style>
