<template>
  <TheHeader />
  <About/>
</template>

<script>
import TheHeader from "@/components/TheHeader.vue"
import About from "../components/About.vue";

export default {
  components: { TheHeader, About },
};
</script>
