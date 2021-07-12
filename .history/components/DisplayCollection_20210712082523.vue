<template>
  <div class="container">
    <div class="row">
      <div class="col-md-6 col-sm-12 col-12">
        <div class="row">
          <div class="col-12 pb-4 d-flex align-items-center">
            <div class="men-collection all-collection">
              <h3>Mens</h3>
              <p>Collection</p>
            </div>
          </div>
          <div class="col-12 d-flex align-items-center">
            <div class="women-collection all-collection">
              <h3>Women's</h3>
              <p>Collection</p>
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

<style>
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
</style>
