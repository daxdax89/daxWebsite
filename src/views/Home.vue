<template>
  <div class="home">
    <TopSection></TopSection>
  </div>
</template>

<script>
// @ is an alias to /src
import TopSection from "@/components/TopSection.vue";

export default {
  name: "home",
  components: {
    TopSection
  }
};
</script>