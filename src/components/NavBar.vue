<template>
  <header>
    <nav class="pb-0 mb-2">
      <div class="titleimage flex bg-cover bg-center h-[150px] mt-2 mb-2">
        <h1 class="text-[3rem] m-auto">Krystal Clear Mental Health</h1>
      </div>
      <div class="h-[25px] bg-[#f3dfdf]">
        <div class="float-left pl-2 space-x-4 m-auto">
          <router-link to="/">Home</router-link>
          <router-link to="/about">About</router-link>
          <router-link to="/contact">Contact</router-link>
        </div>
        <div v-if="$store.state.user" class="float-right pr-2 m-auto">
          <router-link to="/login">Logout</router-link>
        </div>
        <div v-else class="float-right pr-2 m-auto">
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
  color: #5c5e7a;
}

nav a.router-link-exact-active {
  color: #55596b;
  filter: drop-shadow(0 0 0.06rem rgb(80, 69, 69));
}
</style>

<script>
import { onBeforeMount } from "vue";
import { useStore } from "vuex";

export default {
  name: "NavBar",
  setup() {
    const store = useStore();
    onBeforeMount(() => {
      store.dispatch("fetchUser");
    });
  },
};
</script>
