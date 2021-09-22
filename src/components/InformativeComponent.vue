<template>
  <div class="CustomContainer">
    <div class="overlay"></div>
    <div
      class="
        content
        d-flex
        flex-column
        justify-content-center
        align-items-center
      "
    >
      <p class="subHeading">
        Lorem ipsum dolor sit amet, consecetur adipiscing elit . Vicamus lacinia
        odio vitea vestibulum vestibulum
      </p>
      <h1 class="text-center title">TITLE</h1>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.title {
  font-weight: bolder;
  font-size: 3rem;
  color: #fff;
  margin-bottom: 30px;
  filter: brightness(1) !important;
}

.subHeading {
  color: #fff;
  font-size: 2rem;
  margin-bottom: 50px;
  margin-top: 20px;
  display: inline-block;
  vertical-align: middle;
  filter: brightness(1) !important;
  width: 75%;
}
.CustomContainer {
  height: 100vh;
  width: 100%;
  background-repeat: no-repeat;
  background-size: cover;
  position: relative;
}

.overlay {
  width: 100%;
  height: 100%;
  background-image: url("/img/1285.jpg");
  filter: sepia(100%) hue-rotate(190deg) saturate(400%) brightness(0.4);
  position: absolute;
  top: 0;
  left: 0;
}
.content {
  width: 100%;
  height: 100%;
}
@media (max-width: 766px) {
  .container {
    padding-top: 10vh;
    padding-bottom: 10vh;
  }
}
@media (max-width: 350px) {
  .container {
    padding-top: 5vh;
  }
}
</style>
