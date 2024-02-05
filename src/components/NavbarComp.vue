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
</template>

<script>
  export default {
    
  }
</script>

<style>
.navbar {
  background-color: #3E3232;
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
</style>