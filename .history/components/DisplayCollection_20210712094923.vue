<template>
  <div class="container mb-5">
    <div class="row">
      <div class="col-md-6 col-sm-12 col-12">
        <div class="row">
          <div class="col-12 pb-4">
            <div
              class="men-collection all-collection d-flex align-items-center"
            >
              <div class="collection-content">
                <h3>Mens</h3>
                <p>Collection</p>
              </div>
            </div>
          </div>
          <div class="col-12 pb-4">
            <div
              class="women-collection all-collection d-flex align-items-center"
            >
              <div class="collection-content">
                <h3>Women's</h3>
                <p>Collection</p>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="col-md-6 col-sm-12 col-12">
        <div class="accessories all-collection d-flex align-items-center">
          <div class="collection-content">
            <h3>Accessories</h3>
            <p>Collection</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script></script>

<style scoped>
.men-collection {
  background-image: url('@/assets/Images/mens.png');
  height: 300px;
}
.women-collection {
  background-image: url('@/assets/Images/women.png');
  height: 300px;
}
.accessories {
  background-image: url('@/assets/Images/accessories.png');
  height: 623px;
}
.all-collection {
  background-repeat: no-repeat;
  background-position: bottom;
  background-size: cover;
  border-radius: 15px;
}
.collection-content {
  margin-left: 60px;
}
.collection-content h3 {
  color: white;
  font-weight: 500;
}
.collection-content p {
  color: white;
}
@media only screen and (min-width: 320px) and (max-width: 767px) {
  .accessories {
    height: 300px;
  }
}
</style>
