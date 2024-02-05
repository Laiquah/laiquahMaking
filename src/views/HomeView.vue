<template>
  <div>
    <nav class="navbar navbar-expand-lg">
  <div class="container-fluid">
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav m-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <router-link to="/">HOME</router-link>
        </li>
        <li class="nav-item">
          <router-link to="/about">ABOUT</router-link>
        </li>
        <li class="nav-item">
          <router-link to="/shop">SHOP</router-link>
        </li>
        <li class="nav-item">
          <router-link to="/contact">CONTACT</router-link>
        </li>
      </ul>
    </div>
  </div>
</nav>
  </div>
  <section class="banner">
      <div class="overlay">
        <div class="div1">
          <h1 class="h1">PlatinumDrive</h1>
          <h2 class="h2">"Where Luxury Meets the Open Road"</h2>
        </div>
      </div>
  </section>
  <section class="section1">
    <h3 class="h3">FEATURED PRODUCTS</h3>
    <center>
      <div class="row">
    <div class="col-3">
      <div class="card">
        <img src="https://i.ibb.co/cwtzg4V/bmw-ix-m60-onepager-gallery-impressions-thumbnail-02.jpg" class="card-img-top" alt="BMW iX M60">
        <div class="card-body">
          <h5 class="card-title">BMW iX M60</h5>
          <p class="card-text">This is a longer card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
        </div>
      </div>
    </div>
    <div class="col-3">
      <div class="card">
        <img src="https://i.ibb.co/Jd25tqr/2024-bmw-i7-m70-119-643d69e564b2a.jpg" class="card-img-top" alt="BMW i7">
        <div class="card-body">
          <h5 class="card-title">BMW i7</h5>
          <p class="card-text">This is a longer card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
        </div>
      </div>
    </div>
    <div class="col-3">
      <div class="card">
        <img src="" class="card-img-top" alt="...">
        <div class="card-body">
          <h5 class="card-title">Card title</h5>
          <p class="card-text">This is a longer card with supporting text below as a natural lead-in to additional content.</p>
        </div>
      </div>
    </div>
    <div class="col-3">
      <div class="card">
        <img src="" class="card-img-top" alt="...">
        <div class="card-body">
          <h5 class="card-title">Card title</h5>
          <p class="card-text">This is a longer card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
        </div>
      </div>
    </div>
  </div>
    </center>
  </section>
</template>

<script>
export default {
}
</script>

<style>
.navbar {
  background-color: #030609;
}

a{
  color: white !important;
  text-decoration: none !important;
}

.nav-item{
  margin-left: 5%;
    font-size: 154%;
    font-weight: 900;
}
.banner {
  position: relative;
  background-image: url("https://i.ibb.co/WG7bFMv/pexels-akbar-nemati-10397720.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  height: 80vh;
}

.overlay {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: rgba(0, 0, 0, 0.5); /* Adjust the opacity by changing the last value (0 to 1) */
}

.h1{
  padding-top: 7%;
    color: white !important;
    font-weight: 900 !important;
    font-size: 901% !important;
}

.h2{
  color: white !important;
  font-weight: 100 !important;
  font-style: italic !important;
}

.h3{
  color: black !important;
    font-weight: 900 !important;
    font-size: 293% !important;
    text-decoration: underline;
    padding-top: 4%;
}

.div1{
  padding-top: 5%;
}

.card-img-top{
  width: 40% !important;
}

.card{
  width: 40% !important;
}
</style>
