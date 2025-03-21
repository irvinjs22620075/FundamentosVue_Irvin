<script setup>
</script>

<template>
    <!-- Inicio del col-md-6 para los juegos mas populares -->
    <div class="col-md-6">
        <div class="card mt">
            <div style="background-color: #E94560;" class="card-header">
                <h1
                    style="color: beige; font-size: 40px; font-family: 'Open Sans', sans-serif; 
                    text-transform: uppercase; letter-spacing: 3px; text-shadow: 3px 3px 10px rgba(0, 0, 0, 0.5);">
                    VIDEOJUEGOS MÁS POPULARES </h1>
            </div>
            <div class="card-body">
                <!-- inicio de carrusel de reproduccion automatico -->
                <div id="carouselExampleAutoplaying" class="carousel slide" data-bs-ride="carousel">
                    <div class="carousel-inner">
                        <div class="carousel-item active">
                            <img src="/imagenes/fortnite.jpg" class="d-block w-100" alt="Videojuego 1">
                        </div>
                        <div class="carousel-item">
                            <img src="/imagenes/Apex.jpg" class="d-block w-100" alt="Videojuego 2">
                        </div>
                        <div class="carousel-item">
                            <img src="/imagenes/pubg.jpg" class="d-block w-100" alt="Videojuego 3">
                        </div>
                        <div class="carousel-item">
                            <img src="/imagenes/Gears.jpg" class="d-block w-100" alt="Videojuego 4">
                        </div>
                        <div class="carousel-item">
                            <img src="/imagenes/COD.jpg" class="d-block w-100" alt="Videojuego 5">
                        </div>
                    </div>
                    <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleAutoplaying"
                        data-bs-slide="prev">
                        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                        <span class="visually-hidden">Previous</span>
                    </button>
                    <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleAutoplaying"
                        data-bs-slide="next">
                        <span class="carousel-control-next-icon" aria-hidden="true"></span>
                        <span class="visually-hidden">Next</span>
                    </button>
                    <!-- fin del carrusel de reproduccion automatico -->
                </div>
            </div>
        </div>
    </div>
    <!-- Final del col-md-6 para los juegos mas populares -->
</template>

<style scoped></style>