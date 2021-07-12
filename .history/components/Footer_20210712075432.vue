<template>
  <footer id="footer">
    <div class="container">
      <div class="row">
        <div class="col-md-3 col-lg-4 col-sm-6 col-12">
          <p>
            <span>leather</span>
            <span>brand</span>
          </p>
          <ul class="social-icon list-unstyled d-flex">
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
                <img :src="require('@/assets/Images/instagram.svg')" alt="" />
              </a>
            </li>
            <li>
              <a href="">
                <img :src="require('@/assets/Images/twitter.svg')" alt="" />
              </a>
            </li>
          </ul>
        </div>
        <div class="col-md-3 col-lg-2 col-sm-6 col-12">
          <h5>About</h5>
          <ul class="list-unstyled">
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
          <h5>Information</h5>
          <ul class="list-unstyled">
            <li><a href="">Terms & Conditions</a></li>
            <li><a href="">Payment Options</a></li>
            <li><a href="">Privacy Policy</a></li>
          </ul>
        </div>
        <div class="col-md-3 col-sm-6 col-12">
          <h5>Customer service</h5>
          <ul class="list-unstyled">
            <li><a href="">FAQs</a></li>
            <li><a href=""></a>Store Locator</li>
          </ul>
        </div>
        <div class="col-md-3 col-lg-2 col-sm-6 col-12">
          <h5>Contact Info</h5>
          <ul class="list-unstyled">
            <li><a href="">+88029824275</a></li>
            <li><a href="">example@gmail.com</a></li>
            <li><a href="">Tongi, Gazipur</a></li>
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
</style>
