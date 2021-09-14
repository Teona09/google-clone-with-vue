<template>
    <div class="Google-Logo">
        <img
          v-bind:src="logo"
          alt="Google Logo"
          title="Google Search"
        />
      </div>
</template>

<script>
import googleLogo from "../../../assets/Google-Logo.png";
// fara import nu merge imaginea folosing v-bind chiar daca ii dau path-ul mai jos
export default {
  data() {
    return {
      logo: googleLogo,
    };
  },
};
</script>