<template>
  <Banner />
  <div class="main-container">
    <h1>Monte o seu Hamburguer:</h1>
  </div>
  <BurgerForm />
</template>

<script>
import Banner from "../components/Banner.vue";
import BurgerForm from "../components/BurgerForm.vue";
export default {
  components: {
    Banner,
    BurgerForm,
  },
  data() {},
};
</script>
