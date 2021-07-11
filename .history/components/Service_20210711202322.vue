<template>
  <div class="container">
    <div class="row">
      <div v-for="service in services" :key="service.id">
        <h3>{{ service.title }}</h3>
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
