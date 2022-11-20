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
  background-color: #eff1f5;
  background-color: #24273a;
  background-color: #fdfdfd;
  background-color: #f9b6b5;
}

.card {
  background-color: #f9b6b5;
  background-color: #efefef;
  margin: 0 auto 100px;
  box-shadow: 0 0 20px 0 rgba(0, 0, 0, 0.2), 0 5px 5px 0 rgba(0, 0, 0, 0.24);
}

*,
*:before,
*:after {
  font-family: Quicksand, Avenir, Helvetica, Arial, sans-serif, "Special Elite";
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

input,
textarea {
  outline: none;
}

button,
input[type="submit"] {
  outline: none;
  border: none;
}

button:hover,
input[type="submit"] {
  cursor: pointer;
  transform: translateY(-0.25em);
}

li,
a {
  text-decoration: none;
}

body {
  background-color: #eff1f5;
  background-color: #fdfdfd;
  background-color: #24273a;
  background-color: #f9b6b5;
  min-height: 100vh;
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
