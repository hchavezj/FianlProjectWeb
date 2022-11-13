<template>
  <header>
    <nav class="pb-20">
      <div class="flex space-x-4 justify-center text-[1.3rem] p-2">
        <router-link to="/">Home</router-link>
        <router-link to="/about">About</router-link>
        <router-link to="/login">Login</router-link>
        <router-link to="/contact">Contact</router-link>
      </div>
      <div class="bg-[#e8e9f5]">
        <h1 class="text-[3rem] font-funk p-3">Krystal Clear Mental Health</h1>
      </div>
    </nav>
  </header>
</template>

<style>
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
};
</script>
