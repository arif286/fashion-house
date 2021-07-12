<template>
  <div class="container mb-5">
    <div class="d-flex justify-content-between">
      <h4>{{ title }}</h4>
      <p class="d-flex">
        <span class="view-product">Views All</span>
        <img :src="require('@/assets/Images/right-arrow.png')" alt="" />
      </p>
    </div>

    <div class="row">
      <div
        v-for="item in products"
        :key="item.id"
        class="col-12 col-sm-6 col-md-3 mb-4"
      >
        <div class="card h-100">
          <div class="card-body">
            <div class="d-flex justify-content-center">
              <img
                class="product-img"
                :src="require(`@/assets/Images/${item.image}`)"
                alt=""
              />
            </div>
            <h3>{{ item.title }}</h3>
            <p>৳{{ item.price }}</p>
            <div>
              <span>star</span>
              <button>shoping</button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  props: {
    products: {
      type: Array,
      required: true,
    },
    title: {
      type: String,
      required: true,
    },
  },
}
</script>

<style scoped>
.product-img {
  width: 190px;
  height: 184px;
}
.card {
  background-color: #f5f5f5;
}
</style>
