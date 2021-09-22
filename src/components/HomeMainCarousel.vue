<template>
  <div>
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
            <div class="btn carouselExplore">Explore</div>
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
          title: "Title Here",
          text: "Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.",
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
  font-size: 1.3rem;
  margin-left: 5vw;
  filter: drop-shadow(0 0 5px #000);
  width: 50%;
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
  font-size: 7vmax;
  color: #fff;
  margin-left: 5vw;
  filter: drop-shadow(0 0 5px #000);
}
@media (max-width: 768px) {
  .carouselText {
    font-size: 1rem;
    width: 80%;
  }
}
</style>