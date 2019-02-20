<template>
  <div>
    <hr class="featurette-divider">
    <h2 class="featurette-heading text-center">What are you waiting for! Get to that party!</h2>
    <hr class="featurette-divider">

    <div class="row featurette">
      <div class="col-md-7">
        <h2 class="featurette-heading">Collect the red balloons for points.
          <br>
          <br>
          <span class="text-muted py-4">Try to beat your top score!</span>
        </h2>
      </div>
      <div class="col-md-5">
        <img
          src="../assets/balloon-points.png"
          alt="Collect balloons for points! Try to beat your high score!"
          class="rounded"
        >
      </div>
    </div>

    <hr class="featurette-divider">

    <div class="row featurette">
      <div class="col-md-7 order-md-2">
        <h2 class="featurette-heading text-right">Avoid obstacles...
          <br>
          <br>
          <span class="text-muted text-right">or the game will restart!</span>
        </h2>
      </div>
      <div class="col-md-5 order-md-1">
        <img
          src="../assets/avoid-obstacles.png"
          alt="Avoid obstalces on the game will restart!"
          class="rounded float-left"
        >
      </div>
    </div>

    <hr class="featurette-divider">

    <div class="row featurette">
      <div class="col-md-7">
        <h2 class="featurette-heading">Collect items along the way.
          <br>
          <br>
          <span class="text-muted">Don't forget your party hat!</span>
        </h2>
      </div>
      <div class="col-md-5">
        <img
          src="../assets/collect-items02.png"
          alt="Collect items along the way. Don't forget your party hat!"
          class="rounded"
        >
      </div>
    </div>

    <hr class="featurette-divider">
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.featurette-divider {
  margin: 5rem 0; /* Space out the Bootstrap <hr> more */
}

/* Thin out the marketing headings */
.featurette-heading {
  font-weight: 300;
  line-height: 1;
  letter-spacing: -0.05rem;
}
</style>


