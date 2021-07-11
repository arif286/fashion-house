<template>
  <div class="container">
    <div class="row">
      <div
        v-for="service in services"
        :key="service.id"
        class="col-md-4 col-12"
      >
        <img :src="`@/assets/Images/${service.image}`" alt="" />
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
<style></style>
