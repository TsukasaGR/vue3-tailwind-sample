<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" class="m-auto" />
    <HelloWorld msg="Welcome to Your Vue.js + TypeScript App" />
    <TailwindSample />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import HelloWorld from "@/components/HelloWorld.vue"; // @ is an alias to /src
import TailwindSample from "@/components/TailwindSample.vue";

export default defineComponent({
  name: "Home",
  components: {
    HelloWorld,
    TailwindSample
  }
});
</script>
