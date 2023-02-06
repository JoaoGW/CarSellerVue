<template>
  <header>
    <NavBar/>
  </header>

  <body>
    <section>
      <FeaturedNews/>
    </section>
    <main>
      <section class="modelos">
        <ModelosTodos/>
      </section>
      <section class="motivacao">
        <MotivacaoCompra/>
      </section>
      <section class="parceiro">
        <ParceirosCompra/>
      </section>
      <section class="ajuda">
        <PrecisaAjuda/>
      </section>
    </main>

    <footer>
      <RodapeFixo/>
    </footer>
  </body>
</template>

<script lang="ts">

import { defineComponent } from 'vue';
import NavBar from './components/navbar.vue'
import FeaturedNews from './components/featured.vue'
import ModelosTodos from './components/modelos.vue'
import MotivacaoCompra from './components/motivos.vue'
import ParceirosCompra from './components/parceiros.vue'
import PrecisaAjuda from './components/ajuda.vue'
import RodapeFixo from './components/footer.vue'

export default defineComponent ({
  components: {
    NavBar,
    FeaturedNews,
    ModelosTodos,
    MotivacaoCompra,
    ParceirosCompra,
    PrecisaAjuda,
    RodapeFixo
  }
})
  
</script>

<style>
  *{
    font-family: 'Montserrat', sans-serif;
  }

  main{
    max-width: 80%;
    margin: 0 auto;
  }

  .modelos, .motivacao, .parceiro, .ajuda{
    margin-bottom: 3rem;
  }

  h1, h2, h3{
    font-size: 35px;
  }
</style>