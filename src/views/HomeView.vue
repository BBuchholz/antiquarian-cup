<template>
  <div class="home">
    <img alt="SCA logo" src="../assets/SCA_LOGO.png" />
    <HelloWorld msg="Welcome to Your Vue.js + TypeScript App" />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import HelloWorld from "@/components/HelloWorld.vue"; // @ is an alias to /src

export default defineComponent({
  name: "HomeView",
  components: {
    HelloWorld,
  },
});
</script>

<style>
img {
  max-width: 100%;
  height: auto;
}
</style>
