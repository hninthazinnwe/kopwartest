<template>
  <div class="home">
    <a  name="home"></a>
    <div class="d-flex justify-content-end ps-5">
      <div class="row">
      <div class="col-lg-5 ps-5">
        <h1>Download Your Kopwar App</h1>
        <p class="my-4 text-muted">Please download and install on your phone ..! Thanks</p>
        <div class="btn btn-warning btn-lg px-4 me-3">Google Play</div>
        <div class="btn btn-warning btn-lg px-4">For Huawei Phone</div>
        <h3>Coming Soon App Store</h3>
      </div>
      <div class="col-lg-6 ps-5">
        <div class="device-wrapper">
          <div class="device">
            <img src="../assets/img/pic_1.jpg" width="260" height="500" />
          </div>
        </div>
      </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
   name: 'home' 
}
</script>
<style>
  h1 {
    font-size: 3rem;
    font-weight: 800 !important;
    line-height: 1.5;
  }
  h3 {
    font-size: 2rem;
    font-weight: 800 !important;
  }
  .home {
    background: url(../assets/img/banner-4.png) no-repeat;
    background-size: 100% 80%;
    font-family: "Montserrat", sans-serif;
    color: #17141f !important;
    position: inherit;
    padding-top: 200px;
  }
  .device-wrapper {
    max-width: 300px;
    width: 100%;
    margin-left: 50px;
    z-index: 1;
    position: relative;
  }
  .device {
    padding: 50px 20px;
    border-radius: 3rem;
    box-shadow: 0 5px 25px rgb(0 0 0 / 8%) !important;
  }
</style>