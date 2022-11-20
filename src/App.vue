<template>
  <div id="app">
    <NavBar title="Krystal Clear Mental Health" />
    <router-view />
    <PageFooter />
  </div>
</template>

<style>
#app {
  font-family: Quicksand, Avenir, Helvetica, Arial, sans-serif, "Special Elite";
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #cad3f5;
  color: #2c3e50;
  background-color: #f9b6b5;
  margin: auto;
  text-align: center;
  max-width: 80%;
}

.card {
  background-color: #fff;
  margin: 0 auto;
  box-shadow: 0 0 20px 0 rgba(0, 0, 0, 0.2), 0 5px 5px 0 rgba(0, 0, 0, 0.24);
}

*,
*:before,
*:after {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

li,
a {
  text-decoration: none;
}

body {
  background-color: #f9b6b5;
}
</style>

<script type="text/javascript">
import NavBar from "@/components/NavBar.vue";
import PageFooter from "@/components/PageFooter.vue";

export default {
  components: {
    NavBar,
    PageFooter,
  },
};
</script>
