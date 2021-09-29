<template>
  <div class="container-fluid">
    <div class="container">
      <h1 class="text-center">TITLE</h1>
      <p class="subHeading">
        Lorem ipsum dolor sit amet, consecetur adipiscing elit . Vicamus lacinia
        odio vitea vestibulum vestibulum
      </p>
      <div class="row text-white">
        <div class="col-md-4 mb-2 col-sm-12">
          <h1 class="text-center">1200+</h1>
          <p>Text</p>
        </div>
        <div class="col-md-4 mb-2 col-sm-12">
          <h1 class="text-center">2000+</h1>
          <p>Active Members</p>
        </div>
        <div class="col-md-4 mb-2 col-sm-12">
          <h1 class="text-center">100+</h1>
          <p>Community</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.row p {
  font-weight: 300;
  text-align: center;
}
.row {
  margin-top: 100px;
}
h1 {
  font-weight: bolder;
  font-size: 4vmax;
  color: #fff;
}
.subHeading {
  color: #fff;
  font-size: 1.1rem;
  margin-bottom: 50px;
  margin-top: 20px;
  text-align: center;
}
.container-fluid {
  background-color: #231f20;
  background-image: url(/img/dotsPattern.png),
    url(/img/dotsPatternBottomRight.png);

  background-position: right bottom, left top;
  background-repeat: no-repeat;
}
.container {
  padding: 100px 15px;
}
</style>
