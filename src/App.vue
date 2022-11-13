<template>
  <div id="app">
    <NavBar />
    <router-view />
  </div>
</template>

<style>
#app {
  color: #cad3f5;
  color: #2c3e50;
  background-color: #eff1f5;
  background-color: #f9b6b5;
  background-color: #24273a;
  background-color: #fdfdfd;
  margin: auto;
}

* {
  font-family: Quicksand, Avenir, Helvetica, Arial, sans-serif, "Special Elite";
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  min-height: 100vh;
  background-color: #eff1f5;
  background-color: #f9b6b5;
  background-color: #24273a;
  background-color: #fdfdfd;
  border-left: 1px solid black;
  border-right: 1px solid black;
}
</style>

<script type="text/javascript">
import NavBar from "@/components/NavBar.vue";
export default {
  components: {
    NavBar,
  },
};
</script>
