<template>
  <nav class="navbar container navbar-expand-lg navbar-light mb-3">
    <div class="container-fluid">
      <div class="nav-title">
        <span>leather</span>
        <br />
        <span>brand</span>
      </div>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div id="navbarSupportedContent" class="collapse navbar-collapse">
        <div class="d-flex justify-content-center w-100">
          <ul class="navbar-nav mb-2 mb-lg-0">
            <li class="nav-item">
              <a class="nav-link active" href="#"
                >Men
                <img
                  class="down-arrow"
                  :src="require('@/assets/Images/down-arrow.png')"
                  alt=""
              /></a>
            </li>
            <li class="nav-item">
              <a class="nav-link active" href="#"
                >Women
                <img
                  class="down-arrow"
                  :src="require('@/assets/Images/down-arrow.png')"
                  alt=""
              /></a>
            </li>
            <li class="nav-item">
              <a class="nav-link active" href="#">
                Accessories
                <img
                  class="down-arrow"
                  :src="require('@/assets/Images/down-arrow.png')"
                  alt=""
                />
              </a>
            </li>
            <li class="nav-item">
              <a class="nav-link active" href="#">Blogs</a>
            </li>
          </ul>
        </div>
        <div class="ml-auto">
          <ul class="navbar-nav mb-2 mb-lg-0">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#"
                ><img
                  class="nav-icon"
                  :src="require('@/assets/Images/search.png')"
                  alt=""
              /></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"
                ><img
                  class="nav-icon"
                  :src="require('@/assets/Images/nav-bag.png')"
                  alt=""
              /></a>
            </li>
            <li class="nav-item">
              <a class="nav-link active" href="#">
                <img
                  class="nav-icon"
                  :src="require('@/assets/Images/avatar.png')"
                  alt=""
                />
              </a>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </nav>
</template>

<script></script>
<style scoped>
.nav-title {
  color: #521010;
  font-weight: 900;
  font-size: 18px;
}
.nav-title:hover {
  color: #521010;
  font-weight: bold;
}
.nav-item a {
  color: #000;
}
.nav-icon {
  width: 20px;
}
.nav-link {
  font-weight: 500;
}
.down-arrow {
  width: 12px;
}
</style>
