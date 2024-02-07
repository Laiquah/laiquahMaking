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
  <div class="card-details">
    <img src="https://i.ibb.co/1R8m6HJ/image-1639072627192.jpg" alt="" loading="lazy" class="img">
  </div>
  <button class="card-button">BMW iX M60</button>
</div>
    </div>
    <div class="col-3">
      <div class="card">
  <div class="card-details">
    <img src="https://i.ibb.co/sqMYcsq/cosySec.png" alt="" loading="lazy" class="img3">
  </div>
  <button class="card-button">BMW i7</button>
</div>
    </div>
    <div class="col-3">
      <div class="card">
  <div class="card-details">
    <img src="https://i.ibb.co/4tsCCLS/4-175-f.webp" alt="" loading="lazy" class="img">
  </div>
  <button class="card-button">BMW iX3</button>
</div>
    </div>
    <div class="col-3">
      <div class="card">
  <div class="card-details">
    <img src="https://i.ibb.co/vLZ6dWQ/image-1674190647214.jpg" alt="" loading="lazy" class="img">
  </div>
  <button class="card-button">BMW X6</button>
</div>
    </div>
  </div>
    </center>
  </section>
  <section>
    <center>
      <div class="divBtn2">
        <router-link to="/about" class="divBtn">CHECKOUT OUR ABOUT PAGE</router-link>
      </div>
    </center>
  </section>
  <div class="footer">
    Copyright &copy; {{ newYear }}, All Right Reserved
</div>
</template>

<script>
export default {
  data() {
    return {
      newYear: new Date().getUTCFullYear(),
    };
  },
}
</script>

<style>
.footer{
  background-color: #030609;
  color: white;
  font-size: 154%;
    font-weight: 900;
}
.navbar {
  background-color: #030609;
}

.divBtn2{
  padding-top: 100px;
  padding-bottom: 100px;
}

.divBtn {
  border: 5px solid black;
  background-color: black;
  width: 15% !important;
  border-radius: 8px;
  padding: 10px;
}

.divBtn:hover{
  background-color:  rgb(134, 134, 134);
  color: black !important;
  border: 5px solid  rgb(134, 134, 134);
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

.card {
 width: 95%;
 height: 70vh;
 border-radius: 20px;
 background: #f5f5f5;
 position: relative;
 padding: 1.8rem;
 border: 2px solid #c3c6ce !important;
 transition: 0.5s ease-out;
 overflow: visible;
}

.card-details {
 color: black;
 height: 100%;
 gap: .5em;
 display: grid;
 place-content: center;
}

.card-button {
 transform: translate(-50%, 125%);
 width: 60%;
 border-radius: 1rem;
 border: none;
 background-color: #030609;
 color: #fff;
 font-size: 1rem;
 padding: .5rem 1rem;
 position: absolute;
 left: 50%;
 bottom: 0;
 opacity: 0;
 transition: 0.3s ease-out;
}

.text-body {
 color: rgb(134, 134, 134);
}

/*Text*/
.text-title {
 font-size: 1.5em;
 font-weight: bold;
}

/*Hover*/
.card:hover {
 border-color: #030609;
 box-shadow: 0 4px 18px 0 rgba(0, 0, 0, 0.25);
}

.card:hover .card-button {
 transform: translate(-50%, 50%);
 opacity: 1;
}

.row{
  --bs-gutter-x: 0rem !important;
  padding-top: 4%;
}

.img{
  width: 95%
}

.img3{
  width: 89%
}
</style>
