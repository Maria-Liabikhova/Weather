<template>
  <div class="flex flex-col min-h-screen font-Roboto bg-weather-primary">
    <SiteNavigation />
    <RouterView />
  </div>
</template>
<!-- https://www.youtube.com/watch?v=NilffTjcDVA&ab_channel=TheNetNinja -->
<script setup>
import { RouterView } from "vue-router";
import SiteNavigation from "./components/SiteNavigation.vue";
</script>

<style lang="scss" scoped>
</style>