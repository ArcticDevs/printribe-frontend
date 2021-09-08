<template>
  <div class="container-fluid bgBlue">
    <div class="container">
      <h1>Title</h1>
      <p class="subHeading">
        Lorem ipsum dolor sit amet, consecetur adipiscing elit . Vicamus lacinia
        odio vitea vestibulum vestibulum
      </p>
      <div class="row">
        <b-card
          title="Card Title"
          img-src="/Black_full.png"
          img-alt="Image"
          img-top
          tag="article"
          style="max-width: 20rem;"
          class="mb-2 border-0 col-md-4 col-sm-12 mx-auto"
        >
          <b-card-text>
            Some quick example text to build on the card title and make up the
            bulk of the card's content.
          </b-card-text>
        </b-card>
        <b-card
          title="Card Title"
          img-src="/Black_full.png"
          img-alt="Image"
          img-top
          tag="article"
          style="max-width: 20rem;"
          class="mb-2 border-0 col-md-4 col-sm-12  mx-auto"
        >
          <b-card-text>
            Some quick example text to build on the card title and make up the
            bulk of the card's content.
          </b-card-text>
        </b-card>
        <b-card
          title="Card Title"
          img-src="/Black_full.png"
          img-alt="Image"
          img-top
          tag="article"
          style="max-width: 20rem;"
          class="mb-2 border-0 col-md-4 col-sm-12  mx-auto"
        >
          <b-card-text>
            Some quick example text to build on the card title and make up the
            bulk of the card's content.
          </b-card-text>
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
.card {
  background-color: transparent !important;
  margin-right: 45px;
}
.card-body {
  background-color: #231f20;
}
.card-body .card-title,
h4 {
  color: #fdbf64;
}
.card-text {
  color: #ffffff;
}
.bgBlue {
  background-color: #29649d;
  padding: 50px 0 50px 0;
}
</style>
