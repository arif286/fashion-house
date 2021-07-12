<template>
  <div class="container">
    <div class="row">
      <div class="col-md-6 col-12">
        <div class="card">
          <div class="card-body">
            <h4>{{}}</h4>
            <p>{{}}</p>
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
