<template>
  <nav class="navbar navbar-expand-lg navbar-light  shadow-sm fixed-top">
      <div class="container">
        <img src="~/assets/logo.png" alt="" style="width: 100px;">
        
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav ms-auto">
            <li class="nav-item">
              <a class="nav-link" aria-current="page" href="#Home">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#about">about</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#product">product</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="https://wa.me/6289663692024">contact me</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
</template>

<style>
.nav-link:active::content {
  text-decoration: underline;
}

.navbar{
background: #f2a1c7;

}
</style>