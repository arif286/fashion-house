<template>
  <div class="container">
    <div class="row">
      <div
        v-for="service in services"
        :key="service.id"
        class="col-md-4 col-12"
      >
        <div class="service-box">
          <img :src="require(`@/assets/Images/${service.image}`)" alt="" />
          <h3>{{ service.title }}</h3>
          <p>{{ service.text }}</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    services: { type: Array, required: true },
  },
}
</script>
<style>
.service-box {
  width: 250px;
}
</style>
