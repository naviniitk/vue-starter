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
  <div class="form">
    <div class="form-text">Sign Up!</div>
    <div class="form-wrapper">
      <InputItem label="First Name" />
      <InputItem label="Last Name" />
      <InputItem label="Email" />
      <InputItem label="Organization" />
      <InputItem label="Password" />
      <SubmitButton text="Submit" />
    </div>
  </div>
</template>

<style scoped>
.form {
  display: flex;
  flex-direction: column;
  margin: auto;
  height: 100%;
  justify-content: center;
}
.form-text {
  font-weight: 600;
  font-size: 32px;
  text-align: center;
}
.form-wrapper {
  display: flex;
  flex-direction: column;
  margin: 0;
  padding: 60px 100px;
  background-color: white;
}
@media (max-width: 1000px) {
  .form-wrapper {
    padding: 60px 15vw;
  }
}
@media (max-width: 400px) {
  .form-wrapper {
    padding: 30px 10px;
  }
}
</style>
