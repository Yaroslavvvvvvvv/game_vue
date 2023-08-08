<template>
  <div class="app">
    <img class="logo animate__animated animate__backInRight" src="./assets/logo.png" alt="Vue logo">
    <h1 class="h1 animate__animated animate__backInLeft">Remember Me</h1>
    <p>Remember and open all green cells</p>
    <v-boards></v-boards>
  </div>
</template>

<script>


import VBoards from "@/components/VueBoard.vue";

export default {
  name: 'App',
  components: {
    VBoards
  }
}
</script>

<style scoped>
.app {
  font-family: Helvetica,sans-serif;
  margin-top: 40px;
  text-align: center;
}
.logo {
  width: 100px;
}
</style>
