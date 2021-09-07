<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-md-6 col-sm-12 p-0">
        <img src="/Model1.png" class="ModelImage" />
      </div>
      <div class="col-md-6 col-sm-12 bgProduct1">
        <div class="container-custom container">
          <h1>Title</h1>
          <p>
            LOREM IPSUM DOLOR SIT AMET, CONSECTETUR ADIPISCING ELIT. RATIO
            QUIDEM VESTRA SIC COGIT. DUO REGES: CONSTRUCTIO INTERRETE. HAERET IN
            SALEBRA. GRACCHO, EIUS FERE, AEQUALí? QUORUM ALTERA PROSUNT, NOCENT
            ALTERA. IDEMNE, QUOD IUCUNDE?
          </p>
          <div class="btn1">
            ORDER NOW
          </div>
        </div>
      </div>
    </div>
    <div class="row">
      <div class="col-md-6 col-sm-12 bgProduct2">
        <div class="container-custom container">
          <h1>Title</h1>
          <p>
            LOREM IPSUM DOLOR SIT AMET, CONSECTETUR ADIPISCING ELIT. RATIO
            QUIDEM VESTRA SIC COGIT. DUO REGES: CONSTRUCTIO INTERRETE. HAERET IN
            SALEBRA. GRACCHO, EIUS FERE, AEQUALí? QUORUM ALTERA PROSUNT, NOCENT
            ALTERA. IDEMNE, QUOD IUCUNDE?
          </p>
          <div class="btn1">
            START SELLING
          </div>
        </div>
      </div>
      <div class="col-md-6 col-sm-12 p-0">
        <img src="/Model2.png" class="ModelImage" />
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scroped>
.container-custom {
  margin: 50vh 30px 0 30px;
  width: 700px;
}
.container-custom h1 {
  font-weight: 600;
  font-size: 70px;
  color: #fff;
  text-align: left;
}
.container-custom p {
  color: #fff;
  text-align: left;
}

.btn1 {
  background-color: #231f20;
  color: #fff;
  width: 20rem;
  padding: 20px;
  font-size: 25px;
  margin-top: 30px;
}
.btn1:hover {
  color: #fff;
  cursor: pointer;
}
.ModelImage {
  object-fit: cover;
  width: 100%;
}
.bgProduct1 {
  background-color: #fb8f27;
}
.bgProduct2 {
  background-color: #ef3e2e;
}

@media(max-width:1451px){
    .container-custom {
  margin: 40vh 30px 0 30px;
  width: 700px;
}

}
@media(max-width:1290px){
    .container-custom {
  margin: 30vh 50px 0 50px;
  width: 700px;
}

}
@media(max-width:1059px){
    .container-custom {
  margin: 20vh 50px 0 50px;
  width: 700px;
}

}

@media(max-width:1024px){
    .container-custom {
  margin: 12vh 50px 0 50px;
  width: 700px;
}

}
@media(max-width:768px){
    .container-custom {
  margin: 8vh 50px 0 50px;
  width: 700px;
}

}
@media(max-width:414px){
    .container-custom {
  margin: 4vh 50px 30px 50px;
  width: 700px;
}
.btn1 {
  background-color: #231f20;
  color: #fff;
  width: 15rem;
  padding: 20px;
  font-size: 25px;
  margin-top: 30px;
}

}

@media(max-width:320px){
    .container-custom {
  margin: 2vh 50px 30px 50px;
  width: 700px;
}

}




 
</style>
