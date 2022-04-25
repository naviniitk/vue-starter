<script setup lang="ts">
import InputItem from "../components/input-item.vue";
import SubmitButton from "../components/submit-button.vue";
</script>

<template>
  <form>
    <InputItem label="Email" />
    <InputItem label="Password" />
    <SubmitButton text="Submit" />
  </form>
</template>
