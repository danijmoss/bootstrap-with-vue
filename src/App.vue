<template>
  <div id="app">
    <SiteHeader/>
    <HomeCarousel/>
    <div class="container marketing">
      <HomeMarketing/>
      <HomeFeaturette/>
    </div>
    <SiteFooter/>
  </div>
</template>

<script>
import SiteHeader from "./components/Shared/SiteHeader.vue";
import HomeCarousel from "./components/HomeCarousel.vue";
import HomeMarketing from "./components/HomeMarketing.vue";
import HomeFeaturette from "./components/HomeFeaturette.vue";
import SiteFooter from "./components/Shared/SiteFooter.vue";

export default {
  name: "app",
  components: {
    SiteHeader,
    HomeCarousel,
    HomeMarketing,
    HomeFeaturette,
    SiteFooter
  }
};
</script>

<style>
body {
  padding-top: 3rem;
  padding-bottom: 3rem;
  color: #5a5a5a;
}

/* RESPONSIVE CSS
-------------------------------------------------- */

@media (min-width: 40em) {
  /* Bump up size of carousel content */
  .carousel-caption p {
    margin-bottom: 1.25rem;
    font-size: 1.25rem;
    line-height: 1.4;
  }

  .featurette-heading {
    font-size: 50px;
  }
}

@media (min-width: 62em) {
  .featurette-heading {
    margin-top: 7rem;
  }
}
</style>
