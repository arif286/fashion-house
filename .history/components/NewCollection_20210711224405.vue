<template>
  <div class="container">
    <div class="row">
      <div v-for="item in collections" :key="item.id" class="col-md-6 col-12">
        <div class="card">
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
<style></style>
