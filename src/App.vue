<script>
  import Header from "./components/Header.vue";
  import Main from "./components/Main.vue";
  import Companies from "./components/Companies.vue";
  import Products from "./components/Products.vue";
  import Testemunials from "./components/Testemunials.vue";
  import Footer from "./components/Footer.vue";

  export default {
    name: "App",
    components: {
      Header,
      Main,
      Companies,
      Products,
      Testemunials,
      Footer
    }
  }

</script>

<template>
  <Header />
  <Main />
  <Companies />
  <Products />
  <Testemunials />
  <Footer />
</template>

<style scoped>

</style>
