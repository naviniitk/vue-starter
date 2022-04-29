<script lang="ts">
export default {
  name: "SubmitButton",
  props: {
    text: String,
  },
};
</script>

<template>
  <o-button variant="primary" class="btn">Submit</o-button>
</template>

<style scoped>
.btn {
  background-color: #ff6f61;
  border-style: none;
  padding: 16px;
  border-radius: 4px;
  cursor: pointer;
}
.btn:hover {
  background-color: #dd4124;
  transition: 0.3s;
}
</style>
