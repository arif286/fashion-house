<template>
  <div>
    <Nav />
    <Slider />
    <Service :services="serviceData" />
  </div>
  <NewCollection :collections="collections" />
</template>

<script>
import { serviceData, newCollectionData } from '@/assets/data.js'
export default {
  data() {
    return {
      serviceData,
      collections: newCollectionData,
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
  max-width: 1780px;
}
</style>
