<template>
  <div class="carouselContainer">
    <div class="container-fluid p-0">
      <carousel :items="1" :loop="true" :nav="false" :dots="false">
        <div
          class="slideContainer"
          v-for="(item, index) in carouselItems"
          :key="index"
        >
          <img :src="item.img" class="carouselIMG" />
          <div class="textPosition">
            <h1 class="carouselTitle">{{ item.title }}</h1>
            <p class="mr-5 carouselText">
              {{ item.text }}
            </p>
            <div class="btn carouselExplore" v-if="item.text.length">
              Explore
            </div>
          </div>
        </div>
      </carousel>
    </div>
  </div>
</template>

<script>
import carousel from "vue-owl-carousel2";

export default {
  components: { carousel },
  data() {
    return {
      slide: 0,
      sliding: null,
      carouselItems: [
        {
          img: "/img/1285.jpg",
          title: "What’s Printribe?",
          text: "A one stop destination to let your ideas come alive! Whether you are an artist who loves to design or someone who runs a business which sells creative products, we are what you need to elevate your business to a whole new level. We trust your idea, you got to trust us to showcase it. Let the limelight be on you & the grind on us!",
        },
        {
          img: "/img/1284.jpg",
          title: "",
          text: "",
        },
        {
          img: "/img/1281.jpg",
          title: "",
          text: "",
        },
      ],
    };
  },
  methods: {
    onSlideStart(slide) {
      this.sliding = true;
    },
    onSlideEnd(slide) {
      this.sliding = false;
    },
  },
};
</script>

<style scoped>
.carouselContainer {
  height: calc(100vh - 60px);
  overflow: hidden;
}
.slideContainer {
  position: relative;
  height: calc(100vh - 60px);
}
.carousel-caption {
  min-width: 100% !important;
  background-color: black !important;
}
.carouselText {
  color: #fff;
  font-size: 1.2rem;
  margin-left: 5vw;
  filter: drop-shadow(0 0 5px #000);
  width: 60%;
}
.carouselExplore {
  padding: 15px;
  width: 30vw;
  min-width: 200px;
  margin-left: 5vw;
  font-size: 3vh;
  background-color: #ef3e2e;
  color: #fff;
  font-weight: 600;
  filter: drop-shadow(0 0 5px #000);
}
.textPosition {
  position: absolute;
  bottom: 15%;
  text-align: left;
  margin-left: 5vw;
}
.carouselIMG {
  width: 100%;
  height: 100%;
  object-fit: cover;
}
.carouselTitle {
  font-weight: bolder;
  font-size: 4.5vmax;
  color: #fff;
  margin-left: 5vw;
  filter: drop-shadow(0 0 5px #000);
}
@media (max-width: 768px) {
  .carouselText {
    font-size: 0.9rem;
    width: 80%;
  }
}

@media (min-width: 1540px) {
  .carouselText {
    font-size: 1.5rem;
  }
}
</style>