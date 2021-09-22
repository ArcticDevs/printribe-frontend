<template>
  <div class="container-fluid bgBlue">
    <div class="container">
      <h1 class="text-center">Title</h1>
      <p class="subHeading">
        Lorem ipsum dolor sit amet, consecetur adipiscing elit . Vicamus lacinia
        odio vitea vestibulum vestibulum
      </p>
      <div class="row">
        <b-card
        v-for="(item, index) in cardItems" :key="index"
          :title="item.title"
          :img-src="item.img"
          img-alt="Image"
          img-top
          tag="article"
          style="max-width: 20rem"
          class="mb-2 border-0 col-md-4 col-sm-12 mx-auto"
        >
          <b-card-text>
            {{item.text}}
          </b-card-text>
        </b-card>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      cardItems:[
        {
          title:"Card Title",
          img:"/img/661.png",
          text:"Some quick example text to build on the card title and make up the bulk of the card's content."
        },
        {
          title:"Card Title",
          img:"/img/662.png",
          text:"Some quick example text to build on the card title and make up the bulk of the card's content."
        },
        {
          title:"Card Title",
          img:"/img/663.png",
          text:"Some quick example text to build on the card title and make up the bulk of the card's content."
        },
      ]
    };
  },
};
</script>

<style scoped>
h1 {
  font-weight: bolder;
  font-size: 60px;
  color: #fff;
  text-align: center;
}
.subHeading {
  color: #fff;
  font-size: 30px;
  margin-bottom: 50px;
  margin-top: 20px;
  text-align: center;
}

.card {
  background-color: transparent !important;
  margin-right: 45px;
  filter: drop-shadow(0 0 3px #000);
}

.card-img-top {
  background: #131212;
  border-radius: 10px 10px 0 0;
}
.card-body {
  background-color: #332e2f;
  border-radius: 0 0 10px 10px;
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
  background-image: url(/img/dotsPattern.png);
  background-repeat: no-repeat;
}
</style>
