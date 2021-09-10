<template>
  <div class="home">
    <Navbar />
    <div class="carouselContainer">
    <Carousel/>
    </div>
    <ProductCard />
    <Pricing />
    <Productdisplay />
    <InformativeComponent />
    <Stats />
    <Subscribe />
    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import Navbar from "@/components/navBar.vue";
import Carousel from "@/components/HomeMainCarousel.vue";
import ProductCard from "@/components/ProductCard.vue";
import Pricing from "@/components/pricing.vue";
import Productdisplay from "@/components/Productdisplay.vue";
import Stats from "@/components/Stats.vue";
import Subscribe from "@/components/subscribe.vue";
import Footer from "@/components/footer.vue";
import InformativeComponent from "@/components/InformativeComponent.vue";
InformativeComponent
export default {
  name: "Home",
  components: {
    Navbar,
    Carousel,
    ProductCard,
    Pricing,
    Productdisplay,
    Stats,
    Subscribe,
    Footer,
    InformativeComponent,
  },
};
</script>


<style scoped>
.carouselContainer{
  height: calc(100vh - 60px);
  overflow: hidden;
}
</style>