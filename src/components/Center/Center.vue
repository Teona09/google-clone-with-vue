<template>
  <section class="center">
    <Logo></Logo>
    <SearchForm></SearchForm>
    <SearchButtons></SearchButtons>
    <LanguageList></LanguageList>
  </section>
</template>

<script>
// idee din proiectul lui Fineas -> HeaderNavbar.vue
import Logo from "./center-items/Logo.vue";
import SearchForm from "./center-items/SearchForm.vue";
import SearchButtons from "./center-items/SearchButtons.vue";
import LanguageList from "./center-items/LanguageList.vue";

export default {
  name: "App",
  components: {
    Logo,
    SearchForm,
    SearchButtons,
    LanguageList,
  },
};
</script>

<style>
@import "../styles/center.css";
</style>
