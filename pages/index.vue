<template>
    <div id="carousel" class="carousel slide" data-bs-ride="carousel">
        <div class="carousel-inner">
            <div class="carousel-item active">
                <img src="~/assets/gambar1.jpg" class="d-block w-100" alt="gambar1">
            </div>
        </div>
    </div>

    <!-- about -->
    <section id="about" class="pt-5">
        <div class="card mb-3 shadow" style="max-width: 100%;">
            <div class="row g-0">
                <div class="col-md-4">
                    <img src="~/assets/about-image.jpeg" class="img-fluid rounded-start p-4 " alt="...">
                </div>
                <div class="col-md-8">
                    <div class="card-body">
                        <h2 class="about card-title text-center">About us</h2>
                        <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Excepturi ipsam
                            expedita laudantium id vel ab voluptatem pariatur voluptatibus explicabo ad, eius esse ipsum
                            minus fugit incidunt consequuntur porro cupiditate iure.
                        </p>
                        <p class="card-text"><small class="text-muted">lebih lanjut</small></p>
                        <!-- contact -->
                        <a href="https://www.instagram.com/" target="_blank"class="bg-primary text-light text-center shadow"
                            style="width: 30%;border-radius: 50px; display: block; text-decoration:none">Open</a>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- about n  -->

    <!-- product -->
    <section id="product">
        <div class="container">
            <div class="row text-center">
                <div class="col pt-5">
                    <h2>Product</h2>
                </div>
            </div>
            <div class="row d-flex justify-content-around pt-5">
                <div class="card" style="width: 18rem;">
                    <img src="~/assets/jaguar.jpeg" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title text-center">Jaguar</h5>
                        <p class="card-text">IDR 285.000</p>
                        <a href="#" class="btn btn-primary">Open</a>
                    </div>
                </div>
                <div class="card" style="width: 15rem;">
                    <img src="~/assets/avrill.jpeg" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title text-center">avrill</h5>
                        <p class="card-text">IDR 285.000</p>
                        <a href="#" class="btn btn-primary">Open</a>
                    </div>
                </div>
                <div class="card" style="width: 18rem;">
                    <img src="~/assets/bulgary.jpeg" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title text-center">Jaguar</h5>
                        <p class="card-text">IDR 285.000</p>
                        <a href="#" class="btn btn-primary">Open</a>
                    </div>
                </div>
            </div>
        </div>
    </section>


    <!-- n -->
    <!-- footer -->
    <div class="card mt-5 shadow">
        <div class="card-body">
            <div class="image d-flex justify-content-center">
                <img src="~/assets/logo.png" style="width:150px;" alt="logo">
            </div>
            
            <div class="pt-3 d-flex justify-content-center">
                <p>Jl.ciwasmandi</p>
            </div>
            <div class="d-flex justify-content-center">
                <p>&copy Rumah Parfum Damara</p>
            </div>
        </div>
    </div>
    <!-- contact wa -->
    <a href="https://wa.me/6289505898529" class="wa-button fixed-bottom" target="_blank">
        <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg" alt="WhatsApp" class="wa-icon">
        Hubungi Admin
    </a>
    <!-- footer -->
</template>


<style>

.wa-button {
    width: 200px;
    background-color: #25d366;
    color: white;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 50px;
    font-size: 16px;
    font-weight: bold;
    transition: background-color 0.3s ease;
}

.wa-button:hover {
    background-color: #22b35a;
}

.wa-icon {
    width: 24px;
    height: 24px;
    margin-right: 10px;
}
</style>