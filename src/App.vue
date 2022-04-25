<script lang="ts">
import FormWrapper from "./components/form-wrapper.vue";
export default {
  name: "App",
  components: {
    FormWrapper: FormWrapper,
  },
};
</script>

<template>
  <FormWrapper />
</template>

<style>
:root {
  background-color: #0f0f11;
}
#app {
  margin: 0;
  padding: 2rem;
  margin: 0px auto;
}
</style>
