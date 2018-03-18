<template>
  <div id="app">
    <my-header></my-header>
    <h1>{{ msg }}</h1>
    <my-footer></my-footer>
  </div>
</template>

<script>
import MyHeader from "./components/header/Header.vue";
import MyFooter from "./components/footer/Footer.vue";

export default {
  name: "app",
  data() {
    return {
      msg: "Welcome to Your Vue.js App"
    };
  },
  components: {
    MyHeader,
    MyFooter
  }
};
</script>

<style lang="scss">

</style>
