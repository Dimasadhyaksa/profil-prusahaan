<template>
  <nav class="navbar navbar-expand-lg  shadow-sm fixed-top" >
    <div class="image">

      <img src="~/assets/logo.png" alt="logo">
    </div>
    <div class="container">

      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link" aria-current="page" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#about">About</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#product">Product</a>
          </li>
          <!-- <li class="nav-item">
              <a class="nav-link" href="#">contact me</a>
            </li> -->
        </ul>
      </div>
    </div>
  </nav>
</template>

<style>
.nav-link:active::content {
  text-decoration: underline;
}
</style>