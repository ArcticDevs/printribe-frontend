<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-sm-6 col-12 p-0">
        <img src="/img/664.png" class="ModelImage" />
      </div>
      <div
        class="
          col-sm-6 col-12
          bgProduct1
          px-sm-5
          py-5
          d-flex
          flex-column
          align-items-center
          justify-content-center
        "
      >
        <h1>Title</h1>
        <p>
          LOREM IPSUM DOLOR SIT AMET, CONSECTETUR ADIPISCING ELIT. RATIO QUIDEM
          VESTRA SIC COGIT. DUO REGES: CONSTRUCTIO INTERRETE. HAERET IN SALEBRA.
          GRACCHO, EIUS FERE, AEQUALí? QUORUM ALTERA PROSUNT, NOCENT ALTERA.
          IDEMNE, QUOD IUCUNDE?
        </p>
        <div class="w-100 text-center">
          <div class="orderBtn">ORDER NOW</div>
        </div>
      </div>
    </div>
    <div class="row">
      <div
        class="
          col-sm-6 col-12
          bgProduct2
          px-sm-5
          py-5
          d-flex
          flex-column
          align-items-center
          justify-content-center
        "
      >
        <h1>Title</h1>
        <p>
          LOREM IPSUM DOLOR SIT AMET, CONSECTETUR ADIPISCING ELIT. RATIO QUIDEM
          VESTRA SIC COGIT. DUO REGES: CONSTRUCTIO INTERRETE. HAERET IN SALEBRA.
          GRACCHO, EIUS FERE, AEQUALí? QUORUM ALTERA PROSUNT, NOCENT ALTERA.
          IDEMNE, QUOD IUCUNDE?
        </p>
        <div class="w-100 text-center">
          <div class="orderBtn">START SELLING</div>
        </div>
      </div>
      <div class="col-sm-6 col-12 p-0">
        <img src="/img/665.png" class="ModelImage" />
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.container {
  padding: 20vh 30px 20px 30px;
}
h1 {
  font-weight: 600;
  font-size: 3.4.5vmax;
  color: #fff;
  text-align: left;
}
p {
  color: #fff;
  text-align: left;
}

.orderBtn {
  background-color: #231f20;
  color: #fff;
  width: 17rem;
  max-width: 100%;
  padding: 15px;
  margin-top: 30px;
  filter: drop-shadow(0 2px 5px rgb(107, 107, 107));
  border-radius: 10px;
}
.orderBtn:hover {
  color: #fff;
  cursor: pointer;
}
.ModelImage {
  object-fit: cover;
  width: 100%;
  /* height: 100%; */
  background: #000;
}
.bgProduct1 {
  background-color: #fb8f27;
  background-image: url(/img/dotsPattern.png),
    url(/img/dotsPatternBottomRight.png);

  background-position: left top, right bottom;
  background-repeat: no-repeat;
}
.bgProduct2 {
  background-color: #ef3e2e;
  background-image: url(/img/dotsPatternBottomLeft.png);

  background-position: right bottom;
  background-repeat: no-repeat;
}

@media (max-width: 414px) {
  .orderBtn {
    background-color: #231f20;
    color: #fff;
    width: 15rem;
    padding: 20px;
    font-size: 25px;
    margin-top: 30px;
  }
}

@media(min-width:1540px){
  h1{
    font-size:4vmax;
  }
}
</style>
