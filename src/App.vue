<script lang="ts">
import MainDashboard from "./components/main-dashboard.vue";
export default {
  name: "App",
  components: {
    MainDashboard,
  },
};
</script>

<template>
  <MainDashboard />
</template>

<style>
:root {
  background-color: #ff6f61;
}
body {
  margin: 0;
}
#app {
  display: flex;
  height: 100vh;
}
</style>
