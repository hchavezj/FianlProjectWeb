<template>
  <header>
    <nav class="pb-4">
      <div class="titleimage flex bg-cover bg-center h-[150px] m-auto" style="">
        <h1 class="text-[3rem] m-auto">{{ title }}</h1>
      </div>
      <div class="h-[25px] bg-[#f3dfdf]">
        <div class="float-left pl-2 space-x-4 m-auto">
          <router-link to="/">Home</router-link>
          <router-link to="/about">About</router-link>
          <router-link to="/contact">Contact</router-link>
        </div>
        <div class="float-right pr-2 m-auto">
          <router-link to="/login">Login</router-link>
        </div>
      </div>
    </nav>
  </header>
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
  name: "NavBar",
  props: ["title"],
};
</script>
