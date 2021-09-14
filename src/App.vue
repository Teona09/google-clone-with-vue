<template>
  <Header></Header>
  <Center></Center>
  <Footer></Footer>
</template>

<script>
import Header from "./components/Header.vue";
import Center from "./components/Center/Center.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "App",
  components: {
    Header,
    Center,
    Footer,
  },
};
</script>

<style>
@import "style.css";
</style>
