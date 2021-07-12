<template>
  <div class="container mb-5">
    <h3>{{}}</h3>

    <div class="row">
      <div
        v-for="item in products"
        :key="item.id"
        class="col-md-4 col-sm-6 col-12"
      >
        <div class="card">
          <div class="card-body">
            <img :src="require(`@/assets/Images/${item.image}`)" alt="" />
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
  },
}
</script>
