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
    <input class="my-input" />
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
.my-input {
  display: flex;
  width: 100%;
  height: 40px;
  border: 0;
  border-radius: 5px;
  font-size: 16px;
  outline: none;
  background-color: #f3f3f4;
}
.my-input:hover {
  background-color: white;
  border: 3px solid #fda199;
  transition: 0.2s;
}
.label {
  padding: 5px 0px;
  font-size: 20px;
  color: black;
  font-family: "Montserrat";
}
</style>
