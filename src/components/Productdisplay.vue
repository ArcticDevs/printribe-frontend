<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-md-6 col-sm-12 p-0">
        <img src="/img/664.png" class="ModelImage" />
      </div>
      <div class="col-md-6 col-sm-12 bgProduct1">
        <div class="bgImage">
          <div class="container">
            <h1>Title</h1>
            <p>
              LOREM IPSUM DOLOR SIT AMET, CONSECTETUR ADIPISCING ELIT. RATIO
              QUIDEM VESTRA SIC COGIT. DUO REGES: CONSTRUCTIO INTERRETE. HAERET
              IN SALEBRA. GRACCHO, EIUS FERE, AEQUALí? QUORUM ALTERA PROSUNT,
              NOCENT ALTERA. IDEMNE, QUOD IUCUNDE?
            </p>
            <div class="orderBtn">
              ORDER NOW
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="row">
      <div class="col-md-6 col-sm-12 bgProduct2">
        <div class="container">
          <h1>Title</h1>
          <p>
            LOREM IPSUM DOLOR SIT AMET, CONSECTETUR ADIPISCING ELIT. RATIO
            QUIDEM VESTRA SIC COGIT. DUO REGES: CONSTRUCTIO INTERRETE. HAERET IN
            SALEBRA. GRACCHO, EIUS FERE, AEQUALí? QUORUM ALTERA PROSUNT, NOCENT
            ALTERA. IDEMNE, QUOD IUCUNDE?
          </p>
          <div class="orderBtn">
            START SELLING
          </div>
        </div>
      </div>
      <div class="col-md-6 col-sm-12 p-0">
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
.container h1 {
  font-weight: 600;
  font-size: 70px;
  color: #fff;
  text-align: left;
}
.container p {
  color: #fff;
  text-align: left;
}

.orderBtn {
  background-color: #231f20;
  color: #fff;
  width: 20rem;
  padding: 20px;
  font-size: 25px;
  margin-top: 30px;
  filter:drop-shadow(0 2px 5px rgb(107, 107, 107));
  border-radius:10px;
}
.orderBtn:hover {
  color: #fff;
  cursor: pointer;
}
.ModelImage {
  object-fit: cover;
  width: 100%;
  background:#000;
}
.bgProduct1 {
  background-color: #fb8f27;
  background-image: url(/img/dotsPattern.png), url(/img/dotsPatternBottomRight.png);
   
  background-position: left top, right bottom;
  background-repeat: no-repeat;
}
.bgProduct2 {
  background-color: #ef3e2e;
    background-image:  url(/img/dotsPatternBottomLeft.png);
   
  background-position: right bottom;
  background-repeat: no-repeat;
}

@media (max-width: 1451px) {
  .container-custom {
    margin: 40vh 30px 0 30px;
    width: 700px;
  }
}
@media (max-width: 1290px) {
  .container-custom {
    margin: 30vh 50px 0 50px;
    width: 700px;
  }
}
@media (max-width: 1059px) {
  .container-custom {
    margin: 20vh 50px 0 50px;
    width: 700px;
  }
}

@media (max-width: 1024px) {
  .container-custom {
    margin: 12vh 50px 0 50px;
    width: 700px;
  }
}
@media (max-width: 768px) {
  .container-custom {
    margin: 8vh 50px 0 50px;
    width: 700px;
  }
}
@media (max-width: 414px) {
  .container-custom {
    margin: 4vh 50px 30px 50px;
    width: 700px;
  }
  .orderBtn {
    background-color: #231f20;
    color: #fff;
    width: 15rem;
    padding: 20px;
    font-size: 25px;
    margin-top: 30px;
  }
}

@media (max-width: 320px) {
  .container-custom {
    margin: 2vh 50px 30px 50px;
    width: 700px;
  }
}
</style>
