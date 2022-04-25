<script lang="ts">
import InputItem from "./input-item.vue";
import SubmitButton from "./submit-button.vue";
export default {
  name: "FormWrapper",
  components: {
    InputItem: InputItem,
    SubmitButton: SubmitButton,
  },
};
</script>

<template>
  <div>
    <InputItem label="First Name" placeholder="Enter First Name" />
    <InputItem label="Last Name" placeholder="Enter Last Name" />
    <InputItem label="Email" placeholder="Enter Email" />
    <InputItem label="Company Name" placeholder="Enter Company Name" />
    <InputItem label="Password" placeholder="Enter Password" />
    <SubmitButton text="Submit" />
  </div>
</template>

<style scoped>
div {
  display: flex;
  flex-direction: column;
  width: 40%;
  margin: auto;
  padding: 60px 100px;
  background-color: rgb(19, 23, 16);
  border-radius: 20px;
}
</style>
