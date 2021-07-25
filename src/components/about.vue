<template>
    <div class="about">
        <a  name="about"></a>
        <div class="container ps-4">
        <h5 class="h6 font-weight-bold text-uppercase text-primary">SERVICES</h5>
        <h2 class="font-weight-bold mb-5">Kopwar Services</h2>
        <div class="d-flex pb-5">
            <div class="row">
            <div class="col-md-3 me-5">
                <div class="card" style="width: 20rem;">
                    <img
                        src="../assets/img/file.png"
                        class="about-icon"
                        alt=""
                        height="65"
                    />
                    <div class="card-body">
                        <h3 class="font-weight-bold h4 ms-4">Kopwar Mart</h3>
                        <p class="small ms-4">
                        KOPWAR is an online store. Begin as a foodservice provider to business and other service. By using our app, you will never need to go to Market and get your hand dirty. *Currently available in Yangon
                        </p>
                    </div>
                </div>
            </div>
            <div class="col-md-3 mx-5">
                <div class="card" style="width: 20rem;">
                    <img
                        src="../assets/img/map.png"
                        class="about-icon"
                        alt=""
                        height="65"
                    />
                    <div class="card-body">
                        <h3 class="font-weight-bold h4 ms-4">Kopwar Life</h3>
                        <p class="small ms-4">
                        Now we opened KOPWAR ACADEMY for Student (Online Learning System)
                        </p>
                    </div>
                </div>
            </div>
            <div class="col-md-3 mx-5">
                <div class="card" style="width: 20rem;">
                    <img
                        src="../assets/img/point.png"
                        class="about-icon"
                        alt=""
                        height="65"
                    />
                    <div class="card-body">
                        <h3 class="font-weight-bold h4 ms-4">Kopwar Services Provider</h3>
                        <p class="small ms-4">
                        With our fair and transparent pricing, you know you’ll always get a good deal.
                        </p>
                    </div>
                </div>
            </div>
            </div>
        </div>
        </div>
    </div>
</template>
<script>
export default {
    name: 'about'
}
</script>
<style>
.about {
    background: url(../assets/img/service-bg.svg) repeat-y;
    background-size: cover;
    padding: 100px 200px;
    display: flex;
    font-family: "Montserrat", sans-serif;
    color: #17141f !important;
  }
  .about-icon {
      width: 17%;
      margin: 10px 35px;
  }
  .card {
      padding: 50px 20px;
      border-radius: 10px;
  }
</style>