<template>
  <div>
    <div class="container-fluid p-0">
      <carousel :items="1">
        <div class="slideContainer" v-for="n in 5" :key="n">
          <img src="https://placeimg.com/1920/1080/any?3" class="carouselIMG" />
          <div class="textPosition">
            <h1 class="carouselTitle">Title Here</h1>
            <p class="w-50 carouselText">
              Lorem Ipsum is simply dummy text of the printing and typesetting
              industry. Lorem Ipsum has been the industry's standard dummy text
              ever since the 1500s, when an unknown printer took a galley of
              type and scrambled it to make a type specimen book.
            </p>
            <div class="btn carouselExplore">Explore</div>
          </div>
        </div>

        <!-- <div>
          <img src="https://placeimg.com/1920/1080/any?3" class="carouselIMG" />
          <div class="textPosition">
            <h1 class="carouselTitle">Title Here</h1>
            <p class="w-50 carouselText">
              Lorem Ipsum is simply dummy text of the printing and typesetting
              industry. Lorem Ipsum has been the industry's standard dummy text
              ever since the 1500s, when an unknown printer took a galley of
              type and scrambled it to make a type specimen book.
            </p>
            <div class="btn carouselExplore">Explore</div>
          </div>
        </div>
        <div>
          <img src="https://placeimg.com/1920/1080/any?5" />
          <div>
            <h3>Heading 4.</h3>
            <p>
              Lorem Ipsum is simply dummy text of the printing and typesetting
              industry. Lorem Ipsum has been the industry's standard dummy text
              ever since the 1500s, when an unknown printer took a galley of
              type and scrambled it to make a type specimen book.
            </p>
          </div>
        </div> -->
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
.slideContainer{
    position:relative;
    height:calc(100vh - 60px);
}
.carousel-caption {
  min-width: 100% !important;
  background-color: black !important;
}
.carouselText {
  color: #fff;
  font-size: 1.3rem;
  margin-left: 5vw;
}
.carouselExplore {
  padding: 15px;
  width: 30vw;
  min-width:200px;
  margin-left: 5vw;
  font-size: 3vh;
  background-color: #ef3e2e;
  color: #fff;
  font-weight: 600;
}
.textPosition {
  position: absolute;
  top: 20%;
  text-align: left;
  margin-left: 5vw;
}
.carouselIMG {
  width: 100%;
  height: 100%;
  object-fit:cover;
}
.carouselTitle {
  font-weight: bolder;
  font-size: 7vmax;
  color: #fff;
  margin-left: 5vw;
}
@media(max-width:768px){
.carouselText {
  font-size: 1rem;
}
}
</style>