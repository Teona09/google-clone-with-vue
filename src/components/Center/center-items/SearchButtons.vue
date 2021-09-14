<template>
  <div class="search-buttons">
    <button>{{ searchButtonText }}</button>
    <button>
      <a v-bind:href="feelingLuckyButtonLink"> {{ feelingLuckyButtonText }}</a>
    </button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      searchButtonText: "Căutare Google",
      feelingLuckyButtonText: "Mă simt norocos",
      feelingLuckyButtonLink: "https://www.google.com/doodles",
    };
  },
};
</script>

<style>
@import "../../styles/searchButtons.css";
</style>
