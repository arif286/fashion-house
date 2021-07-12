<template>
  <div class="container mb-5">
    <div class="row contact-bg">
      <div class="contact mt-5 mb-5">
        <h3>Stay on track</h3>
        <p>
          Sign up to our newsletter to stay up to date with the latest news,
          products and events from Leatherex.
        </p>
        <div class="subscribe">
          <input type="text" placeholder="Your Email Address" />
          <input type="button" value="Subscribe!" />
        </div>
      </div>
    </div>
  </div>
</template>
<style scoped>
.contact-bg {
  background-image: url('@/assets/Images/newsletter.png');
  background-repeat: no-repeat;
  background-size: cover;
  background-position: bottom;
  border-radius: 25px;
}
.contact {
  margin-left: 50px;
}
.contact h3 {
  color: #521010;
  font-weight: 800;
}
.contact p {
  width: 345px;
  color: #333333;
}
</style>
