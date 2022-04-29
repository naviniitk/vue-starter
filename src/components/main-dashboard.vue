<script lang="ts">
import FormWrapper from "./form-wrapper.vue";
export default {
  name: "MainDashboard",
  components: { FormWrapper },
};
</script>

<template>
  <div class="dashboard">
    <div class="show-items">
      <div class="img-container">
        <img src="/wondering.svg" />
      </div>
    </div>
    <div class="form-element">
      <FormWrapper />
    </div>
  </div>
</template>

<style scoped>
.dashboard {
  display: grid;
  grid-template-columns: 60% 40%;
  width: 100%;
}
.form-element {
  background-color: white;
  padding: auto 0;
  justify-content: center;
}
@media (max-width: 1200px) {
  .dashboard {
    grid-template-columns: auto 500px;
  }
}
@media (max-width: 1000px) {
  .dashboard {
    display: flex;
    flex-direction: column;
  }
  .show-items {
    padding: 50px;
  }
  .form-element {
    padding: 20px;
  }
}
.img-container {
  margin: auto;
  background-color: white;
  width: 80%;
  border-radius: 20px;
}
img {
  width: 100%;
  margin: auto;
}
.show-items {
  margin: auto;
}
</style>
