<template>
  <div class="home">
    <stdpage msg="Welcome to Your Vue.js + TypeScript App" />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import stdpage from "@/components/page.vue"; // @ is an alias to /src

export default defineComponent({
  name: "Home",
  components: {
    stdpage,
  },
});
</script>
