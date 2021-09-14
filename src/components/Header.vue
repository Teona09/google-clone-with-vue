<template>
  <header class="header">
    <div class="menu">
      <div class="redirect-to">
        <a v-bind:href="gmailLink">Gmail</a>
        <a v-bind:href="imagesLink">Imagini</a>
      </div>
      <div class="circles-menu">
        <div class="circle"></div>
        <div class="circle"></div>
        <div class="circle"></div>
        <div class="circle"></div>
        <div class="circle"></div>
        <div class="circle"></div>
        <div class="circle"></div>
        <div class="circle"></div>
        <div class="circle"></div>
      </div>
      <div class="profile-menu">
        <img v-bind:src="profileImage" alt="profile photo" title="Minion" />
      </div>
    </div>
  </header>
</template>

<script>
import ProfileImage from "../assets/profile.jpg";
// fara import nu merge imaginea folosing v-bind chiar daca ii dau path-ul mai jos
export default {
  data() {
    return {
      gmailLink: "https://mail.google.com/mail/&ogbl",
      imagesLink: "https://www.google.ro/imghp?hl=en&ogbl",
      profileImage: ProfileImage,
    };
  },
};
</script>

<style>
@import "./styles/header.css";
</style>
