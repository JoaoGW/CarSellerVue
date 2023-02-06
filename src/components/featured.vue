<template>
    <div class="faixa">
        <div class="faixa__conteudo">
            <p class="faixa__titulo">Mega Promoção</p>
            <p class="faixa__alerta">*Consulte modelos disponíveis na promoção vigente</p>
        </div>
    </div>

    <section class="carrossel">
        <div id="carouselExampleCaptions" class="carousel slide" data-bs-ride="false">
            <div class="carousel-indicators">
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
            </div>
            <div class="carousel-inner">
                <div class="carousel-item active" id="carousel-cat">
                    <img src="../assets/IMGs/carros-basicos.jpg" class="d-block w-100" alt="Carros Basicos" id="carousel-photo">
                      <div class="carousel-caption d-none d-md-block">
                    <h5>Carros Clássicos</h5>
                    <p>Carros comuns do dia a dia que cabem em todos os bolsos. Econômicos e eficientes</p>
                    </div>
                </div>
                <div class="carousel-item" id="carousel-cat">
                    <img src="../assets/IMGs/carros-luxo.jpeg" class="d-block w-100" alt="Carros Luxo" id="carousel-photo">
                    <div class="carousel-caption d-none d-md-block">
                    <h5>Carros de Luxo</h5>
                    <p>Para quem gosta de manter a boa aprência e trazer um conforto a si mesmo e a todos os passageiros</p>
                    </div>
                </div>
                <div class="carousel-item" id="carousel-cat">
                    <img src="../assets/IMGs/carros-super.webp" class="d-block w-100" alt="Super Carros" id="carousel-photo">
                    <div class="carousel-caption d-none d-md-block">
                    <h5>Carros Esportivos</h5>
                    <p>Para os amantes de velocidade e que gostam do som do motor pulsando pelo asfalto</p>
                    </div>
                </div>
            </div>
            <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
            </button>
            <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
            </button>
        </div>
    </section>

    <div class="mouse animate__animated animate__bounce animate__delay-4s animate__infinite">
        <img class="mouse__down" src="../assets/IMGs/scroll-bottom-icon.svg" alt="Mouse Scroll Down">
        <p class="mouse__info">Scroll Down for More!</p>
    </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent ({
    name: 'FeaturedNews'
})
</script>

<style scoped>
    .faixa{
        background: #00419E;
        height: 20%;
    }

    .faixa__conteudo{
        display: flex;
        align-items: center;
        justify-content: center;
        flex-direction: column;
        padding: 20px;
    }

    .faixa__titulo, .faixa__alerta{
        margin: 0;
        color: #FFF;
    }

    .faixa__titulo{
        font-size: 25px;
        -webkit-text-stroke: 2px #D4E500;
        color: white;
        text-shadow:
            4px 4px 0 #000,
            -2px -2px 0 #000,  
            2px -2px 0 #000,
            -2px 2px 0 #000,
            2px 2px 0 #000;
    }

    .faixa__alerta{
        font-size: 12px;
    }

    #carousel-cat{
        height: 70vh;
    }

    #carousel-photo{
        object-fit: cover;
        height: 70vh;
    }

    .mouse{
        display: flex;
        flex-direction: row;
        justify-content: center;
        height: 15vh;
        align-items: center;
    }

    .mouse__down{
        height: 70%;
        margin-right: 30px;
    }

    .mouse__info{
        font-size: 25px;
    }
</style>