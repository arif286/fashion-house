<template>
  <div class="container mb-5">
    <div
      id="carouselExampleIndicators"
      class="carousel slide"
      data-bs-ride="carousel"
    >
      <div class="carousel-indicators">
        <button
          type="button"
          data-bs-target="#carouselExampleIndicators"
          data-bs-slide-to="0"
          class="active"
          aria-current="true"
          aria-label="Slide 1"
        ></button>
        <button
          type="button"
          data-bs-target="#carouselExampleIndicators"
          data-bs-slide-to="1"
          aria-label="Slide 2"
        ></button>
        <button
          type="button"
          data-bs-target="#carouselExampleIndicators"
          data-bs-slide-to="2"
          aria-label="Slide 3"
        ></button>
      </div>
      <div class="carousel-inner">
        <div class="carousel-item active">
          <div>
            <p>20+ Design Variations</p>
            <h2>Premium Oxford Collection</h2>
            <button>View All</button>
          </div>
        </div>
        <div class="carousel-item">
          <div>
            <p>20+ Design Variations</p>
            <h2>Premium Oxford Collection</h2>
            <button>View All</button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script></script>
<style>
.carousel-item {
  background-image: url('@/assets/Images/hero1.png');
  background-repeat: no-repeat;
  height: 100%;
}
</style>
