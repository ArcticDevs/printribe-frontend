<template>
  <div>
    <div id="nav">
      <div>
        <b-navbar toggleable="lg" class="navbar">
       
            <img src="/favicon.jpg" class="Logo" />
         

          <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

          <b-collapse id="nav-collapse" is-nav>
            <!-- Right aligned nav items -->

            <b-navbar-nav class="ml-auto">
              <b-nav-item href="#">Home</b-nav-item>

              <b-nav-item href="#">Sign Up</b-nav-item>
              <b-nav-item href="#">Sign In</b-nav-item>
              <b-nav-item href="#">Dropship Terms</b-nav-item>
              <b-nav-item href="#">Cart</b-nav-item>
              <b-nav-item href="#">
                <b-icon icon="search" aria-hidden="false"> </b-icon
              ></b-nav-item>
            </b-navbar-nav>
          </b-collapse>
        </b-navbar>
      </div>
    </div>
    <div class="container-fluid p-0">
      <carousel :items="1">
        <div>
          <img src="https://placeimg.com/1920/1080/any?4" class="carouselIMG" />
          <div class="textPosition">
            <h1 class="carouselTitle">Title Here</h1>
            <p class="w-50 carouselText">
              Lorem Ipsum is simply dummy text of the printing and typesetting
              industry. Lorem Ipsum has been the industry's standard dummy text
              ever since the 1500s, when an unknown printer took a galley of
              type and scrambled it to make a type specimen book.
            </p>
            <div class="btn carouselExplore ">Explore</div>
          </div>
        </div>

        <div>
          <img src="https://placeimg.com/1920/1080/any?3" class="carouselIMG" />
          <div class="textPosition">
            <h1 class="carouselTitle">Title Here</h1>
            <p class="w-50 carouselText">
              Lorem Ipsum is simply dummy text of the printing and typesetting
              industry. Lorem Ipsum has been the industry's standard dummy text
              ever since the 1500s, when an unknown printer took a galley of
              type and scrambled it to make a type specimen book.
            </p>
            <div class=" btn carouselExplore ">Explore</div>
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
        </div>
      </carousel>
    </div>
  </div>
</template>

<script>
import carousel from "vue-owl-carousel2";
export default {
  name: "HelloWorld",
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

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.carousel-caption {
  min-width: 100% !important;
  background-color: black !important;
}
.carouselText {
  color: #fff;
  font-size: 25px;
  margin-left: 25px;
}
.carouselExplore {
  padding: 15px;
  width: 400px;
  margin-left: 25px;
  font-size: 25px;
  background-color: #ef3e2e;
  color: #fff;
  font-weight: 600;
}
.textPosition {
  position: relative;
  top: 50vh;
  text-align: left;
  margin-left: 25px;
}
.carouselIMG {
  position: absolute;
  width: 100%;
}
.carouselTitle {
  font-weight: bolder;
  font-size: 130px;
  color: #fff;
}
.Logo {
  width: 20%;
  left: 0 !important;
}
.navbar {
  background-color: #231f20;
}
.nav-link {
  color: #fff !important;
  font-size: 20px;
  margin: 0 10px 0 10px;
}

h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
