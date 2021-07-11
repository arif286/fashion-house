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
      </div>
      <div class="carousel-inner">
        <div class="carousel-item active d-flex align-items-center">
          <div class="slider-content">
            <p>20+ Design Variations</p>
            <h1>
              Premium
              <br />
              Oxford Collection
            </h1>
            <button>View All</button>
          </div>
        </div>
        <div class="carousel-item">
          <div class="slider-content">
            <p>20+ Design Variations</p>
            <h1>
              Premium
              <br />
              Oxford Collection
            </h1>
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
  width: 100%;
  background-size: cover;
  height: 687px;
  border-bottom-left-radius: 30px;
  border-bottom-right-radius: 30px;
}
.slider-content {
  margin-left: 80px;
}
.slider-content h1 {
  color: #333333;
}
</style>
