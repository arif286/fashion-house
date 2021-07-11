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
props:{
    services: Array,
}
</script>
<style></style>
