<template>
  <div class="flex flex-col min-h-screen bg-weather-primary">
    <SiteNavigation></SiteNavigation>
    <router-view />
  </div>
</template>

<script>
import SiteNavigation from "./components/SiteNavigation.vue";

export default {
  components: {
    SiteNavigation,
  },
};
</script>
