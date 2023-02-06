<template>
    <div class="parceiro__infos">
        <h3 class="parceiro__titulo">Seja um parceiro da nossa loja</h3>
        <hr>
    </div>
    <div class="parceiro__content">
        <div class="parceiro__esquerdo">
            <img class="parceiro__ilustracao" src="../assets/IMGs/ilustracoes/IlustracaoParceiro.svg" alt="Ilustracao de um parceiro">
        </div>
        <div class="parceiro__direito">
            <p class="parceiro__descricao">Os parceiros da nossa loja possuem beneficios exclusivos de test-drive e aluguel,
                além de descontos exclusivos e maior retorno financeiro ao trocar o seu carro atual por um novo com a gente.
                Clique no botão abaixo e conheça mais sobre o Programa de Parceria*
            </p>
            <button class="parceiro__saibamais" type="button">Saiba Mais</button>
        </div>
    </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent ({
    name: 'ParceirosCompra'
})
</script>

<style scoped>

    .parceiro__content{
        display: flex;
        flex-direction: row;
        margin: 0 auto;
        width: 90%;
        align-items: center;
        column-gap: 50px;
    }

    .parceiro__titulo{
        font-size: 35px;
        color: #000;
    }

    .parceiro__ilustracao{
        height: 400px;
        width: 400px;
        object-fit: cover;
    }

    .parceiro__direito{
        text-align: center;
    }

    .parceiro__saibamais{
        width: 400px;
        margin: 0 auto .4em auto;
        text-align: center;
        height: 50px;
        border-radius: 20px;
        border-color: #00419E;
        transition: 1s all;
    }
    
    .parceiro__saibamais:hover{
        background-color: #00419E;
        border-color: #000;
        color: #FDFDFD;
        transition: 1s all;
    }
</style>