<template>
  <section class="women-banner spad">
    <div class="container-fluid">
      <div class="row">
        <div class="col-lg-12 mt-5">
          <carousel class="product-slider" :items="3" :nav="false" :autoplay="true"  :loop="true" :dots="false" >

            <div class="product-item">
              <div class="pi-pic">
                <img src="img/products/dark01.PNG" alt="" />
                <ul>
                  <li class="w-icon active">
                    <a href="#"><i class="icon_bag_alt"></i></a>
                  </li>
                  <li class="quick-view">
                    <router-link to="/product">+ Quick View</router-link>
                  </li>
                </ul>
              </div>
              <div class="pi-text">
                <div class="catagory-name">T-Shirt</div>
                <router-link to="/product"> <h5>Brinx Dark</h5> </router-link>
                <div class="product-price">
                  $14.00
                  <span>$35.00</span>
                </div>
              </div>
            </div>
            <div class="product-item">
              <div class="pi-pic">
                <img src="img/products/dark02.PNG" alt="" />
                <ul>
                  <li class="w-icon active">
                    <a href="#"><i class="icon_bag_alt"></i></a>
                  </li>
                  <li class="quick-view"><a href="#">+ Quick View</a></li>
                </ul>
              </div>
              <div class="pi-text">
                <div class="catagory-name">T-Shirt</div>
                <a href="#">
                  <h5>Brinx Dark slite</h5>
                </a>
                <div class="product-price">$13.00</div>
              </div>
            </div>
            <div class="product-item">
              <div class="pi-pic">
                <img src="img/products/elite01.PNG" alt="" />
                <ul>
                  <li class="w-icon active">
                    <a href="#"><i class="icon_bag_alt"></i></a>
                  </li>
                  <li class="quick-view"><a href="#">+ Quick View</a></li>
                </ul>
              </div>
              <div class="pi-text">
                <div class="catagory-name">T-Shirt</div>
                <a href="#">
                  <h5>Brinx Elite</h5>
                </a>
                <div class="product-price">$34.00</div>
              </div>
            </div>
            <div class="product-item">
              <div class="pi-pic">
                <img src="img/products/pba01.PNG" alt="" />
                <ul>
                  <li class="w-icon active">
                    <a href="#"><i class="icon_bag_alt"></i></a>
                  </li>
                  <li class="quick-view"><a href="#">+ Quick View</a></li>
                  <li class="w-icon">
                    <a href="#"><i class="fa fa-random"></i></a>
                  </li>
                </ul>
              </div>
              <div class="pi-text">
                <div class="catagory-name">T-Shirt</div>
                <a href="#">
                  <h5>Brinx PBO slince</h5>
                </a>
                <div class="product-price">$34.00</div>
              </div>
            </div>
            <div class="product-item">
              <div class="pi-pic">
                <img src="img/products/pbo02.PNG" alt="" />
                <ul>
                  <li class="w-icon active">
                    <a href="#"><i class="icon_bag_alt"></i></a>
                  </li>
                  <li class="quick-view"><a href="#">+ Quick View</a></li>
                  <li class="w-icon">
                    <a href="#"><i class="fa fa-random"></i></a>
                  </li>
                </ul>
              </div>
              <div class="pi-text">
                <div class="catagory-name">T-Shirt</div>
                <a href="#">
                  <h5>Brinx PBO Kyle</h5>
                </a>
                <div class="product-price">$50.00</div>
              </div>
            </div>
          
          </carousel>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import carousel from 'vue-owl-carousel';

export default {
    name: 'ProductBrinxid',
    components: {
        carousel
    }
}
</script>
<style scoped>
.product-item{
    margin-right: 25px;
}
</style>