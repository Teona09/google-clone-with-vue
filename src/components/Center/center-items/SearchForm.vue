<template>
  <div class="form-container">
    <form>
      <label class="search-icon">
        <img v-bind:src="searchIcon" alt="searc icon" />
      </label>
      <input type="text" v-bind:title="textPopUp" />
      <label class="microphone-icon">
        <img v-bind:src="micIcon" alt="microphone icon" />
      </label>
    </form>
  </div>
</template>

<script>
import micImage from "../../../assets/Google-Mic.png";
import searchImage from "../../../assets/search.png";
export default {
  data() {
    return {
      micIcon: micImage,
      searchIcon: searchImage,
      textPopUp: "Căutați",
    };
  },
};
</script>

<style>
@import "../../styles/searchForm.css";
</style>
