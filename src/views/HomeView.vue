<template>
  <div class="home">
    <TheHeader></TheHeader>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import TheHeader from "@/components/Header/TheHeader.vue"; // @ is an alias to /src

export default defineComponent({
  name: "HomeView",
  components: {
    TheHeader,
  },
});
</script>
