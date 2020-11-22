<template>
  <div class="flex-sample flex flex-col md:flex-row p-4">
    <div class="flex-1 border border-red-500 m-1">
      box1
    </div>
    <div class="flex-1 border-2 border-yellow-200 m-1">
      box2
    </div>
    <div class="flex-1 border-4 border-indigo-300 m-1">
      box3
    </div>
    <div class="flex-1 border-8 border-purple-400 border-opacity-100 m-1">
      box4
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "FlexSample"
});
</script>
