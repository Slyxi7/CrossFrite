<template>
  <div class="main-app">
    <Header></Header>
    <router-view />
  </div>
</template>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.main-app {
  display: flex;
  flex-direction: column;
  background-image: url("../src/assets/background.png");
  background-size: cover;
  background-position: center;
  height: 100vh;
  max-width: 100vw;
}
</style>

<script setup>
import Header from "./components/Header.vue";
</script>
