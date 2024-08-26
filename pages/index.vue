<template>
    <!-- navbar s -->
        <nav class="navbar navbar-expand-lg bg-light position-sticky">
    <div class="container-fluid">
        <img src="/assets/logo.png" alt="logo">
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
        <div class="navbar-nav">
            <a class="nav-link active" aria-current="page" href="#">Home</a>
            <a class="nav-link" href="#">Features</a>
            <a class="nav-link" href="#">Pricing</a>
            <a class="nav-link disabled">Disabled</a>
        </div>
        </div>
    </div>
    </nav>
    <!-- navbar n -->
    <!-- carousel s -->
        <div id="carouselExampleInterval" class="carousel slide" data-bs-ride="carousel">
    <div class="carousel-inner">
        <div class="carousel-item active" data-bs-interval="10000">
        <img src="/assets/gambar1.jpg" class="d-block w-100 h-50" alt="gambar1">
        </div>
        <div class="carousel-item" data-bs-interval="2000">
        <img src="/assets/gambar1.jpg" class="d-block w-100" alt="...">
        </div>
        <div class="carousel-item">
        <img src="/assets/gambar1.jpg" class="d-block w-100" alt="...">
        </div>
    </div>
    <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleInterval" data-bs-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
    </button>
    <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleInterval" data-bs-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
    </button>
    </div>
    <!-- carousel n -->
</template>