<template>
  <div class="language-list">
    <p>{{ paragraphText }}</p>
    <a v-bind:href="language1Link" class="language">{{ language1 }} </a>
    <a v-bind:href="language2Link" class="language">{{ language2 }} </a>
    <a v-bind:href="language3Link" class="language">{{ language3 }}</a>
  </div>
</template>

<script>
export default {
  data() {
    return {
      paragraphText: "Google oferit in:",
      language1: "English",
      language1Link:
        "https://www.google.com/setprefs?sig=0_4pPUYlQS2Ea5WHlHTRBxTRwcGtY%3D&hl=en&source=homepage&sa=X&ved=0ahUKEwiaspu8rdzyAhWihP0HHWu8BqMQ2ZgBCA4",
      language2: "Magyar",
      language2Link:
        "https://www.google.com/setprefs?sig=0_4pPUYlQS2Ea5WHlHTRBxTRwcGtY%3D&hl=hu&source=homepage&sa=X&ved=0ahUKEwiaspu8rdzyAhWihP0HHWu8BqMQ2ZgBCA8",
      language3: "Deutsch",
      language3Link:
        "https://www.google.com/setprefs?sig=0_4pPUYlQS2Ea5WHlHTRBxTRwcGtY%3D&hl=de&source=homepage&sa=X&ved=0ahUKEwiaspu8rdzyAhWihP0HHWu8BqMQ2ZgBCBA",
    };
  },
};
</script>

<style>
@import "../../styles/languageList.css";
</style>
