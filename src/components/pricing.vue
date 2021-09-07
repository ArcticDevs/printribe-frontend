<template>
  <div class="container-fluid bgBlue">
    <div class="container">
      <h1>PRICING</h1>
      <p class="subHeading">
        Lorem ipsum dolor sit amet, consecetur adipiscing elit . Vicamus lacinia
        odio vitea vestibulum vestibulum
      </p>
      <div class="row">
        <b-card
          title="BASIC"
          img-src="/ribbon.png"
          style="max-width: 20rem;background-color:#ef3e2e"
          class="mb-2 border-0 col-md-4 col-sm-12"
        >
          <b-card-text>
            Some quick example text to build on the card title and make up the
            bulk of the card's content.
          </b-card-text>
            <div class="btn">
              150$
          </div>
        </b-card>
        <b-card
          title="PROFESSIONAL"
          img-src="/ribbon.png"
          style="max-width: 20rem;background-color:#29649d"
          class="mb-2 border-0 col-md-4 col-sm-12"
        >
          <b-card-text>
            Some quick example text to build on the card title and make up the
            bulk of the card's content.
          </b-card-text>
            <div class="btn">
              200$
          </div>
        </b-card>
        <b-card
          title="ULTIMATE"
          img-src="/ribbon.png"
          style="max-width: 20rem;background-color:#fb8f27"
          class="mb-2 border-0 col-md-4 col-sm-12"
        >
          <b-card-text>
            Some quick example text to build on the card title and make up the
            bulk of the card's content.
          </b-card-text>
          <div class="btn">
              250$
          </div>
        </b-card>
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
  font-size: 60px;
  color: #fff;
}
.subHeading {
  color: #fff;
  font-size: 30px;
  margin-bottom: 50px;
  margin-top: 20px;
  
}
.btn{
    background-color: #231f20;
    color: #fdbf64;
    width: 15rem;
}
.btn:hover{
    color: #fff;
}
.card {
   margin-right: 45px;
}

.card-body .card-title,.card-text {
  color: #ffffff;
}
.bgBlue {
  background-color: #231f20;
  padding: 50px 0 50px 0;
}
</style>
