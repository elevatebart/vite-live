<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <HelloWorld msg="Hello Vue 3.0 + Vite" />
  <VueLive code="<input />" />
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import "vue-live/lib/vue-live.esm.css";
import { VueLive } from "vue-live";

export default {
  name: "App",
  components: {
    HelloWorld,
    VueLive,
  },
};
</script>
