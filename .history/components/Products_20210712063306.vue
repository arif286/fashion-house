<template>
  <div class="container mb-5">
    <h4>{{ title }}</h4>

    <div class="row">
      <div
        v-for="item in products"
        :key="item.id"
        class="col-12 col-sm-6 col-md-4"
      >
        <div class="card">
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

<style>
.product-img {
  width: 190px;
  height: 184px;
}
</style>
