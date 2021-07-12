<template>
  <footer id="footer">
    <div class="container pt-5 pb-5">
      <div class="row">
        <div class="col-md-3 col-lg-4 col-sm-6 col-12">
          <p class="brand">
            <span>leather</span>
            <br />
            <span>brand</span>
          </p>
          <ul class="social-icon list-unstyled d-flex mt-4">
            <li>
              <a href="">
                <img
                  class="icon"
                  :src="require('@/assets/Images/facebook.svg')"
                  alt=""
                />
              </a>
            </li>
            <li>
              <a href="">
                <img
                  class="icon"
                  :src="require('@/assets/Images/instagram.svg')"
                  alt=""
                />
              </a>
            </li>
            <li>
              <a href="">
                <img
                  class="icon"
                  :src="require('@/assets/Images/twitter.svg')"
                  alt=""
                />
              </a>
            </li>
          </ul>
        </div>
        <div class="col-md-3 col-lg-2 col-sm-6 col-12">
          <h5 class="info">About</h5>
          <ul class="list-unstyled info-list">
            <li>
              <a href="">About Us</a>
            </li>
            <li>
              <a href="">Awards</a>
            </li>
            <li>
              <a href="">Financial Info</a>
            </li>
          </ul>
        </div>
        <div class="col-md-3 col-lg-2 col-sm-6 col-12">
          <h5 class="info">Information</h5>
          <ul class="list-unstyled info-list">
            <li><a href="">Terms & Conditions</a></li>
            <li><a href="">Payment Options</a></li>
            <li><a href="">Privacy Policy</a></li>
          </ul>
        </div>
        <div class="col-md-3 col-sm-6 col-lg-2 col-12">
          <h5 class="info">Customer service</h5>
          <ul class="list-unstyled info-list">
            <li><a href="">FAQs</a></li>
            <li><a href="">Store Locator</a></li>
          </ul>
        </div>
        <div class="col-md-3 col-lg-2 col-sm-6 col-12">
          <h5 class="info">Contact Info</h5>
          <ul class="list-unstyled info-list">
            <li>
              <a href="">
                <img
                  class="info-icon"
                  :src="require('@/assets/Images/phone.svg')"
                  alt=""
                />
                <span>+88029824275</span>
              </a>
            </li>
            <li>
              <a href="">
                <img
                  class="info-icon"
                  :src="require('@/assets/Images/email.svg')"
                  alt=""
                /><span>example@gmail.com</span></a
              >
            </li>
            <li>
              <a href="">
                <img
                  class="info-icon"
                  :src="require('@/assets/Images/location.svg')"
                  alt=""
                /><span>Tongi, Gazipur</span></a
              >
            </li>
          </ul>
        </div>
      </div>
    </div>
  </footer>
</template>
<style scoped>
#footer {
  background-color: #333333;
}
.icon {
  width: 20px;
}
.social-icon li a {
  padding: 16px;
}
.brand {
  color: #ffffff;
  font-size: 25px;
  font-weight: 800;
  margin-left: 18px;
}
.info {
  color: #ffffff;
  margin-top: 10px;
}
.info-list li a {
  color: gray;
}
.info-list li a:hover {
  color: #c8c6c6;
}
.info-list li {
  margin-bottom: 6px;
}
.info-icon {
  width: 12px;
  margin-right: 5px;
}
</style>
