<template>
  <div class="container-fluid bgBlue">
    <div class="container">
      <h1 class="text-center">PRICING</h1>
      <p class="subHeading">
        Lorem ipsum dolor sit amet, consecetur adipiscing elit . Vicamus lacinia
        odio vitea vestibulum vestibulum
      </p>
      <div class="row">
        <div class="mb-2 col-sm-6 col-md-4 mx-auto">
          <b-card
            title="BASIC"
            img-src="/img/ribbon.png"
            style="background-color: #ef3e2e"
            class="w-100 h-100"
          >
            <b-card-text>
              Some quick example text to build on the card title and make up the
              bulk of the card's content.
            </b-card-text>
            <div class="btn">150$</div>
          </b-card>
        </div>
        <div class="mb-2 col-sm-6 col-md-4 mx-auto">
          <b-card
            title="PROFESSIONAL"
            img-src="/img/ribbon.png"
            style="background-color: #29649d"
            class="w-100 h-100"
          >
            <b-card-text>
              Some quick example text to build on the card title and make up the
              bulk of the card's content.
            </b-card-text>
            <div class="btn">200$</div>
          </b-card>
        </div>
        <div class="mb-2 col-sm-6 col-md-4 mx-auto">
          <b-card
            title="ULTIMATE"
            img-src="/img/ribbon.png"
            style="background-color: #fb8f27"
            class="w-100 h-100"
          >
            <b-card-text>
              Some quick example text to build on the card title and make up the
              bulk of the card's content.
            </b-card-text>
            <div class="btn">250$</div>
          </b-card>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
h1 {
  font-weight: bolder;
  font-size: 3.4.5vmax;
  color: #fff;
}
.subHeading {
  color: #fff;
  font-size: 1.2rem;
  margin-bottom: 50px;
  margin-top: 20px;
  text-align: center;
}
.btn {
  background-color: #231f20;
  color: #fdbf64;
  width: 90%;
  position:absolute;
  bottom:20px;
  left:0;
  right:0;
  transform: translateX(-50%,-50%);
  margin:0 auto;
}
.btn:hover {
  color: #fff;
}
.card {
  margin-right: 45px;
  color: #ffffff;
  max-height:400px;
}

.card-img{
  max-height:45%;
  object-fit: contain;
}

.card-body {
  padding-bottom:50px;
  display:flex;
  align-items:center;
  flex-direction: column;
}

.bgBlue {
  background-color: #231f20;
  padding: 50px 0 50px 0;
  background-image: url(/img/dotsPattern.png),
    url(/img/dotsPatternBottomRight.png);
  background-position: left top, right bottom;
  background-repeat: no-repeat;
}
</style>
