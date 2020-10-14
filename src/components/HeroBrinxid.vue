<template>
  <!-- Hero Section Begin -->
  <section class="hero-section">
    <carousel class="hero-items" :items="1" :nav="false" :autoplay="true" :autoplay-timeout="4000" :display="2">
      <div class="single-hero-items set-bg">
        <div class="container">
          <div class="row">
            <div class="col-lg-5">
              <span>T-Shirt Darks,</span>
              <h1>Black friday</h1>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do
                eiusmod tempor incididunt ut labore et dolore
              </p>
              <a href="#" class="primary-btn">Shop Now</a>
            </div>
            <div class="col-lg-5">
              <img src="img/d_dark.jpg" />
            </div>
          </div>
        </div>
      </div>
      <div class="single-hero-items set-bg">
        <div class="container">
          <div class="row">
            <div class="col-lg-5">
              <span>T-Shirt PBO Silence</span>
              <h1>Black friday</h1>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do
                eiusmod tempor incididunt ut labore et dolore
              </p>
              <a href="#" class="primary-btn">Shop Now</a>
            </div>
            <div class="col-lg-5">
              <img src="img/d_pbo.jpg" />
            </div>
          </div>
        </div>
      </div>
    </carousel>
  </section>
  <!-- Hero Section End -->
</template>

<script>
import carousel from 'vue-owl-carousel';

export default {
    name: 'HeroBrinxid',
    components: {
        carousel
    }
}
</script>