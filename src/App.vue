<template>
  <div>
    <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld msg="Hello Vue 3.0 + Vite" />
    <Takechi />
    <router-link to="/">Home</router-link>
    <router-link to="/contact">Contact</router-link>
    <router-view />
  </div>
</template>

<script>
import Takechi from "./components/Takechi.vue";
import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
    Takechi,
  },
  setup() {
    console.log("hello world");
  },
};
</script>


