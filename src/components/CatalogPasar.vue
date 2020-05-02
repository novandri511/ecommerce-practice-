<template>
    <section class="women-banner spad">
      <div class="container-fluid">
        <div class="row">
          <div class="col-lg-12 mt-5">
            <carousel class="product-slider" :autoplay="true" :nav="false" :items="3" :dots="false" style="margin-right: 10px">
              
              <!-- produk pertama start -->
                <!-- gambar produk -->
              <div class="product-item">
                <div class="pi-pic">
                  <img src="img/mickey1.jpg" alt="">
                  <ul>
                    <li><a href="#"><i class="icon_bag_alt"></i></a></li>
                    <li class="quick-view">
                      <router-link to="/product">
                        +Quick View
                      </router-link>
                      </li>
                  </ul>
                </div>
                  <!-- harga produk -->
                <div class="pi-text">
                  <div class="category-name">
                    Coat
                  </div>
                  <a href="#">
                    <h5>Mickey Bags</h5>
                  </a>
                  <div class="product-price">
                    $14.00
                    <span>$35.00</span>
                  </div>
                </div>

              </div>
              <!-- produk pertama end -->

              <!-- produk kedua start -->
                <!-- gambar produk -->
              <div class="product-item">
                <div class="pi-pic">
                  <img src="img/products/women-2.jpg" alt="">
                  <ul>
                    <li><a href="#"><i class="icon_bag_alt"></i></a></li>
                    <li class="quick-view"><a href="product.html">+Quick View</a></li>
                  </ul>
                </div>
                  <!-- harga produk -->
                <div class="pi-text">
                  <div class="category-name">
                    Shoes
                  </div>
                  <a href="#">
                    <h5>Guangzhou sweater</h5>
                  </a>
                  <div class="product-price">
                    $13.00
                    
                  </div>
                </div>

              </div>
              <!-- produk kedua end -->

              <!-- produk ketiga start -->
              
                <!-- gambar produk -->
              <div class="product-item">
                <div class="pi-pic">
                  <img src="img/products/women-3.jpg" alt="">
                  <ul>
                    <li><a href="#"><i class="icon_bag_alt"></i></a></li>
                    <li class="quick-view">
                      <a href="product.html">+Quick View</a>
                      </li>
                  </ul>
                </div>
                  <!-- harga produk -->
                <div class="pi-text">
                  <div class="category-name">
                    Towel
                  </div>
                  <a href="#">
                    <h5>Pure Pineapple</h5>
                  </a>
                  <div class="product-price">
                    $34.00
                    
                  </div>
                </div>

              </div>
              
              <!-- produk ketiga end -->

              <!-- produk ketiga start -->
                <!-- gambar produk -->
              <div class="product-item">
                <div class="pi-pic">
                  <img src="img/products/women-4.jpg" alt="">
                  <ul>
                    <li><a href="#"><i class="icon_bag_alt"></i></a></li>
                    <li class="quick-view"><a href="product.html">+Quick View</a></li>
                     <li class="w-icon">
                        <a href="#"><i class="fa fa-random"></i></a>
                     </li>
                  </ul>
                </div>
                  <!-- harga produk -->
                <div class="pi-text">
                  <div class="category-name">
                    Towel
                  </div>
                  <a href="#">
                    <h5>Pure Pineapple</h5>
                  </a>
                  <div class="product-price">
                    $34.00
                    
                  </div>
                </div>

              </div>
              <!-- produk ketiga end -->

            
            </carousel>
          </div>
        </div>
      </div>
    </section>
</template>

<script>
import carousel from 'vue-owl-carousel';

export default {
  components: {
    carousel
  }
}
</script>

<style>
.product-item{
  margin-right: 10px;
}
</style>