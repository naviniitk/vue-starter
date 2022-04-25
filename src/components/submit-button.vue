<script lang="ts">
export default {
  name: "SubmitButton",
  props: {
    text: String,
  },
};
</script>

<template>
  <button type="submit">{{ text }}</button>
</template>

<style scoped>
button {
  width: 100%;
  background-color: #4caf50;
  color: white;
  padding: 16px 0px;
  margin: 10px 0px;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}
</style>
