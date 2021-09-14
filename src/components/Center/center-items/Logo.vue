<template>
  <div class="Google-Logo">
    <img v-bind:src="logo" alt="Google Logo" title="Google Search" />
  </div>
</template>

<script>
import googleLogo from "../../../assets/Google-Logo.png";
export default {
  data() {
    return {
      logo: googleLogo,
    };
  },
};
</script>
