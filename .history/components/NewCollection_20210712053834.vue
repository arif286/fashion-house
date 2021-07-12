<template>
  <div class="container">
    <div class="row">
      <div
        v-for="item in collections"
        :key="item.id"
        class="col-md-6 col-12 mb-5"
      >
        <div class="card-content" :class="item.class">
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
  border-radius: 25px;
}
.card-body {
  padding: 70px;
}
.card-body button {
  border-radius: 30px;
  width: 120px;
  padding: 7px 15px;
  border: 1px solid #333333;
  color: #333333;
  background: none;
}
.card-body h4 {
  color: #333333;
  font-weight: 700;
}
.card-body p {
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
</style>
