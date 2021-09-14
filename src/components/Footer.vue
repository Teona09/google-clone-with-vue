<template>
  <footer class="footer">
    <div>
      <p>{{country}}</p>
    </div>
    <div class="footer-links">
      <div class="left-footer">
        <ul>
          <li>
            <a
              v-bind:href="aboutLink"
            >
              {{about}}</a
            >
          </li>
          <li>
            <a
              v-bind:href="advertisingLink"
            >
              {{ advertising }}</a
            >
          </li>
          <li>
            <a
              v-bind:href="businessLink"
            >
              {{business}}</a
            >
          </li>
          <li>
            <a v-bind:href="howSearchWorksLink">
              {{howSearchWorks}}</a
            >
          </li>
        </ul>
      </div>
      <div class="right-footer">
        <ul>
          <li>
            <a v-bind:href="privacyLink">
              {{privacy}}</a
            >
          </li>
          <li>
            <a v-bind:href="termsLink"> {{terms}}</a>
          </li>
          <li>
            <!--Pop up menu -->
            <!--Link is for search setting only -->
            <a v-bind:href="settingsLink">{{settings}}</a>
          </li>
        </ul>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  data() {
    return {
      country: "România",
      about: "Despre",
      aboutLink: "https://about.google/?utm_source=google-RO&utm_medium=referral&utm_campaign=hp-footer&fg=1",
      advertising: "Publicitate",
      advertisingLink: "https://ads.google.com/intl/ro_ro/home/?subid=ww-ww-et-g-awa-a-g_hpafoot1_1!o2&utm_source=google.com&utm_medium=referral&utm_campaign=google_hpafooter&fg=1",
      business: "Companii",
      businessLink: "https://www.google.com/services/?subid=ww-ww-et-g-awa-a-g_hpbfoot1_1!o2&utm_source=google.com&utm_medium=referral&utm_campaign=google_hpbfooter&fg=1#?modal_active=none",
      howSearchWorks: "Cum funcționează Căutarea",
      howSearchWorksLink: "https://www.google.com/search/howsearchworks/?fg=1",
      privacy: "Confidențialitate",
      privacyLink: "https://policies.google.com/privacy?hl=ro&fg=1",
      terms: "Termeni",
      termsLink: "https://policies.google.com/terms?hl=ro&fg=1",
      settings: "Setări",
      settingsLink: "https://www.google.com/preferences?hl=ro&fg=1",
    };
  },
};
</script>

<style>
@import "./styles/footer.css";
</style>