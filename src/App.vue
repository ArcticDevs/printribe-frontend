<template>
  <div id="app">
   <navbar />
   <ProductCard />
   <pricing />
   <Productdisplay />
   <Stats />
   <subscribe />
   <Footer />
  </div>
</template>
<script>
// @ is an alias to /src
import navbar from '@/components/navBar.vue'
import ProductCard from '@/components/ProductCard.vue'
import pricing from '@/components/pricing.vue'
import Productdisplay from '@/components/Productdisplay.vue'
import Stats from '@/components/Stats.vue'
import subscribe from '@/components/subscribe.vue'
import Footer from '@/components/footer.vue'
ProductCard
export default {
  name: 'Home',
  components: {
    navbar,
    ProductCard,
    pricing,
    Productdisplay,
    Stats,
    subscribe,
    Footer,
  }
}
</script>


<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
