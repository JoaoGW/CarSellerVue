<template>
    <div>
        <nav class="navbar navbar-expand-lg bg-light">
            <div class="container-fluid">
                <a class="navbar-brand" href="#">
                    <img src="../assets/IMGs/CAR_SELLER.png" alt="Logo" width="30" height="24" class="d-inline-block align-text-top">
                    Car Seller
                </a>
              <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
              </button>
              <div class="collapse navbar-collapse justify-content-end me-5" id="navbarNavDropdown">
                <ul class="navbar-nav">
                  <li class="nav-item">
                    <a class="nav-link active" aria-current="page" href="#">Home</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="#">Modelos</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="#">Preços</a>
                  </li>
                  <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                      Basicos
                    </a>
                    <ul class="dropdown-menu">
                      <li><a class="dropdown-item" href="#">Chevrolet</a></li>
                      <li><a class="dropdown-item" href="#">Ford</a></li>
                      <li><a class="dropdown-item" href="#">Toyota</a></li>
                      <li><a class="dropdown-item" href="#">Nissan</a></li>
                      <li><a class="dropdown-item" href="#">Hyundai</a></li>
                      <li><a class="dropdown-item" href="#">Volkswagen</a></li>
                    </ul>
                  </li>
                  <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                      Luxo
                    </a>
                    <ul class="dropdown-menu">
                      <li><a class="dropdown-item" href="#">Lexus</a></li>
                      <li><a class="dropdown-item" href="#">Mercedes-Benz</a></li>
                      <li><a class="dropdown-item" href="#">BMW</a></li>
                      <li><a class="dropdown-item" href="#">Volvo</a></li>
                      <li><a class="dropdown-item" href="#">Tesla</a></li>
                      <li><a class="dropdown-item" href="#">Audi</a></li>
                    </ul>
                  </li>
                  <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                      Super
                    </a>
                    <ul class="dropdown-menu">
                      <li><a class="dropdown-item" href="#">Lamborghini</a></li>
                      <li><a class="dropdown-item" href="#">Ferrari</a></li>
                      <li><a class="dropdown-item" href="#">McLaren</a></li>
                      <li><a class="dropdown-item" href="#">Maserati</a></li>
                      <li><a class="dropdown-item" href="#">Porsche</a></li>
                      <li><a class="dropdown-item" href="#">Aston Martin</a></li>
                    </ul>
                  </li>
                </ul>
              </div>
            </div>
          </nav>
    </div>
</template>

<script lang="ts">
    import { defineComponent } from 'vue'

    export default defineComponent ({
        name: 'NavBar' //Define o nome do Componente para exportação
    })
</script>