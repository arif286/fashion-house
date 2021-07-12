<template>
  <div class="container">
    <div class="row">
      <div class="col-md-6 col-sm-12 col-12">
        <div class="row">
          <div class="col-12">
            <div class="men-collection all-collection">
              <h3>Mens</h3>
              <p>Collection</p>
            </div>
          </div>
          <div class="col-12">
            <div class="women-collection all-collection">
              <h3>Women's</h3>
              <p>Collection</p>
            </div>
          </div>
        </div>
      </div>
      <div class="col-md-6 col-sm-12 col-12">
        <div class="accessories all-collection">
          <h3>Accessories</h3>
          <p>Collection</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script></script>

<style>
.men-collection {
  background-image: url('@/assets/Images/mens.png');
}
.women-collection {
  background-image: url('@/assets/Images/women.png');
}
.accessories {
  background-image: url('@/assets/Images/accessories.png');
}
.all-collection {
  background-repeat: no-repeat;
  background-position: center center;
  background-size: cover;
}
</style>
