<template>
  <div class="container mb-5">
    <div class="row">
      <div
        v-for="item in collections"
        :key="item.id"
        class="col-md-6 col-12 mb-5"
      >
        <div class="card-content" :class="item.class">
          <div class="card-body product-details">
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
  border-radius: 25px;
  background-position: bottom;
}
.product-details {
  padding: 70px;
}
.product-details button {
  border-radius: 30px;
  width: 120px;
  padding: 7px 15px;
  border: 1px solid #333333;
  color: #333333;
  background: none;
}
.product-details h4 {
  color: #333333;
  font-weight: 700;
}
.product-details p {
  color: #333333;
}
.newArrival h4 {
  color: white;
}
.newArrival p {
  color: white;
}
.newArrival button {
  border: 1px solid white;
  color: white;
}
@media only screen and (min-width: 320px) and (max-width: 560px) {
  .product-details {
    padding: 70px;
  }
}
</style>
