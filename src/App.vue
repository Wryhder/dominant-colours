<script lang="ts">
import { defineComponent } from "vue";

import HomeScreen from "./components/HomeScreen.vue";
// import GameScreen from "./views/GameScreen.vue";

export default defineComponent({
  components: {
    HomeScreen,
  },
});
</script>

<template>
  <div id="app">
    <HomeScreen />
  </div>
</template>

<style>
html {
  height: 100vh;
}

body {
  margin: 0;
  padding: 0;
  width: 100%;
  min-height: 100vh;
}

* {
  box-sizing: border-box;
}

#app {
  height: 100vh;
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
