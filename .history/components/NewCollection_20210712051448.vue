<template>
  <div class="container">
    <div class="row">
      <div
        v-for="item in collections"
        :key="item.id"
        class="col-md-6 col-12 mb-5"
      >
        <div class="card card-content" :class="item.class">
          <div class="card-body">
            <h4>{{ item.title }}</h4>
            <p>{{ item.text }}</p>
            <button>View ALL</button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  props: {
    collections: {
      type: Array,
      required: true,
    },
  },
}
</script>
<style>
.newArrival {
  background-image: url('@/assets/Images/newarrivals1.png');
}
.promo {
  background-image: url('@/assets/Images/promo.png');
}
.card-content {
  background-repeat: no-repeat;
  background-size: cover;
  height: 680px;
}
</style>
