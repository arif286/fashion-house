<template>
  <div class="container mb-5">
    <h3>{{}}</h3>

    <div class="row">
      <div class="col-md-4 col-sm-6 col-12">
        <div class="card">
          <div class="card-body"></div>
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
