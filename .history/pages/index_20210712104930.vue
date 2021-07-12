<template>
  <div>
    <Nav />
    <Slider />
    <Swiper />
    <Service :services="serviceData" />
    <NewCollection :collections="collections" />
    <Products title="New Arrivals" :products="products" />
    <DisplayCollection />
    <Products title="Best Sellers" :products="products" />
    <Contact />
    <Footer />
  </div>
</template>

<script>
import { serviceData, newCollectionData, productsData } from '@/assets/data.js'
import swiper from '~/components/swiper.vue'
export default {
  components: { swiper },
  data() {
    return {
      serviceData,
      collections: newCollectionData,
      products: productsData,
    }
  },
}
</script>
<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap');

.body {
  font-family: 'Roboto', sans-serif;
}
.container {
  max-width: 1880px;
}
</style>
