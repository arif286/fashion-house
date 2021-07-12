<template>
  <div class="container mb-5">
    <div
      id="carouselExampleIndicators"
      class="carousel slide"
      data-bs-ride="carousel"
    >
      <div class="carousel-indicators mb-4">
        <button
          id="radio-btn"
          type="button"
          data-bs-target="#carouselExampleIndicators"
          data-bs-slide-to="0"
          class="active"
          aria-current="true"
          aria-label="Slide 1"
        ></button>
        <button
          id="radio-btn"
          type="button"
          data-bs-target="#carouselExampleIndicators"
          data-bs-slide-to="1"
          aria-label="Slide 2"
        ></button>
      </div>
      <div class="carousel-inner">
        <div class="carousel-item active d-flex align-items-center first-caro">
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
        <div class="carousel-item second-caro">
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
.first-caro {
  background-image: url('@/assets/Images/hero1.png');
  background-repeat: no-repeat;
  width: 100%;
  background-size: cover;
  height: 587px;
  border-radius: 30px;
}
.slider-content {
  margin-left: 80px;
}
.slider-content h1 {
  color: #333333;
  font-weight: 700;
}
.slider-content button {
  border-radius: 30px;
  width: 120px;
  padding: 7px 15px;
  border: 1px solid #521010;
  color: #521010;
  outline: none;
}
button#radio-btn {
  width: 15px;
  height: 15px;
  border-radius: 15px;
  margin-left: 5px;
}
@media only screen and (min-width: 320px) and (max-width: 450px) {
  .carousel-item {
    height: 400px;
  }
  .slider-content {
    margin-left: 20px;
  }
}
</style>
