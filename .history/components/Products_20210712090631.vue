<template>
  <div class="container mb-5">
    <div class="d-flex justify-content-between pb-3">
      <h4>{{ title }}</h4>
      <a class="view-product" href="">
        <p class="d-flex">
          <span>Views All</span>
          <img :src="require('@/assets/Images/right-arrow.png')" alt="" />
        </p>
      </a>
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
              <span
                ><img
                  class="rating"
                  :src="require('@/assets/Images/star.png')"
                  alt=""
              /></span>
              <img
                class="product-img"
                :src="require(`@/assets/Images/${item.image}`)"
                alt=""
              />
            </div>
            <h3>{{ item.title }}</h3>
            <p class="price">৳{{ item.price }}</p>
            <div class="d-flex justify-content-between">
              <p>
                <span>
                  <img
                    class="heart"
                    :src="require('@/assets/Images/heart.png')"
                    alt=""
                  />
                </span>
                <span>
                  <img
                    class="rating"
                    :src="require('@/assets/Images/star.png')"
                    alt=""
                  />
                </span>
                <span>
                  <img
                    class="rating"
                    :src="require('@/assets/Images/star.png')"
                    alt=""
                  />
                </span>
                <span>
                  <img
                    class="rating"
                    :src="require('@/assets/Images/star2.png')"
                    alt=""
                  />
                </span>
              </p>
              <button class="shopping-btn">
                <img :src="require('@/assets/Images/bag.png')" alt="" />
              </button>
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
.view-product {
  color: #521010;
  font-weight: 500;
}
.price {
  color: #521010;
  font-weight: 500;
}
.shopping-btn {
  background-color: #521010;
  padding: 5px 8px;
  border-radius: 5px;
}
.shopping-btn img {
  width: 25px;
  height: 25px;
}
.rating {
  width: 20px;
}
</style>
