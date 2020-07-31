<template>
  <div class="success">
    <!-- Breadcrumb Section Begin -->
    <div class="breacrumb-section text-left">
      <div class="container">
        <div class="row">
          <div class="col-lg-12">
            <div class="breadcrumb-text product-more">
              <router-link to="/">
                <i class="fa fa-home"></i> Home
              </router-link>
              <span>Detail</span>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- Breadcrumb Section Begin -->
    <div class="d-flex success-checkout align-items-center justify-content-center">
      <div class="col col-lg-4 text-center">
        <img src="img/success-buy.png" alt width="294" />
        <h3 class="mt-4">Sukses Terbayar!</h3>
        <p
          class="mt-2"
        >Silakan tunggu update terbaru dari kami via email yang sudah Anda daftarkan sebelumnya.</p>
        <router-link to="/" class="primary-btn pd-cart mt-3">
          <i class="fa fa-home"></i> Back to Home
        </router-link>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Success",
};
</script>
