<template>
  <div class="hero">
    <!-- Desktop -->
    <div class="container d-md-block">
      <div class="row mt-4 mb-5">
        <div class="col-md-6">
          <div class="d-flex h-100">
            <div class="justify-content-center align-self-center">
              <h2>
                <strong>Daftar Barang Kami,</strong>
              </h2>
              <br />
              <br />
              <router-link class="btn btn-lg btn-success" to="/foods">
                <b-icon-arrow-right></b-icon-arrow-right>Order sekarang
              </router-link>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HeroReno",
};
</script>

<style></style>
