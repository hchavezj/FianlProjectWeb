<template>
  <footer class="min-w-full">
    <p class="m-auto">Final Project by Horacio Chavez</p>
  </footer>
</template>

<style>
@import url("https://fonts.googleapis.com/css2?family=Quicksand:wght@400;700&family=Special+Elite&display=swap");

.titleimage {
  background-image: url("../assets/3ccc.jpg");
}
nav a {
  font-weight: bold;
  color: #111111;
  color: #898ba3;
}

nav a.router-link-exact-active {
  color: #8aadf4;
  color: #363a5f;
  color: #a0adeb;
  filter: drop-shadow(0 0 0.06rem rgb(120, 167, 243));
}
</style>

<script>
export default {
  name: "PageFooter",
};
</script>
