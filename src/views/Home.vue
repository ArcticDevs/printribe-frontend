<template>
  <div class="home">
    <Navbar />
    <Carousel/>
    <ProductCard />
    <Pricing />
    <HowItWorks />
    <Productdisplay />
    <Stats />
    <InformativeComponent />
    <Subscribe />
    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from "@/components/navBar.vue";
import Carousel from "@/components/HomeMainCarousel.vue";
import ProductCard from "@/components/ProductCard.vue";
import Pricing from "@/components/pricing.vue";
import HowItWorks from "@/components/HowItWorks.vue";
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
    HowItWorks,
    Productdisplay,
    Stats,
    Subscribe,
    Footer,
    InformativeComponent,
  },
};
</script>

