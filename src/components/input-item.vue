<script lang="ts">
export default {
  name: "InputItem",
  props: {
    label: String,
    placeholder: String,
  },
};
</script>

<template>
  <div class="input-item">
    <div class="label">{{ label }}</div>
    <input :placeholder="placeholder" />
  </div>
</template>

<style scoped>
.input-item {
  display: flex;
  flex-direction: column;
  padding: 10px 0px;
  width: 100%;
  margin: auto;
}
input {
  height: 40px;
  border: 1px solid #ccc;
  border-radius: 5px;
  width: 100%;
}
.label {
  padding: 5px 0px;
  font-size: 20px;
  color: honeydew;
}
</style>
