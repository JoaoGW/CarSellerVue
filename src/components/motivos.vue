<template>
    <div class="motivacao__conteudo">
        <h2 class="motivacao__titulo">Por que comprar conosco?</h2>
        <hr>
        <div class="motivacao__motivos">
            <div class="motivos__um">
                <p class="um__numero">1.</p>
                <p class="um__texto"><strong>Confiabilidade & Segurança</strong> em sua transação. Sem pegadinhas e burocracia! Pague o valor a vista, parcelado, financiado ou como quiser e o carro é seu!</p>
            </div>

            <div class="motivos__dois">
                <p class="dois__numero">2.</p>
                <p class="dois__texto">Oferecemos um <strong>grande catálogo</strong> de veículos que se adaptam a todos os gostos até mesmo para os clientes mais exigentes</p>
            </div>

            <div class="motivos__tres">
                <p class="tres__numero">3.</p>
                <p class="tres__texto"><strong>Sem taxas</strong> abusivas de comissão ou qualquer coisa do tipo. Aqui você negocia diretamente com a concessionária ou com o vendedor sem nenhuma intermediação</p>
            </div>

            <div class="motivos__quatro">
                <p class="quatro__numero">4.</p>
                <p class="quatro__texto"><strong>Pague como quiser</strong>. Seja por cartão de crédito, cartão de débito, carnê, financiamento com o banco ou cheque. Só certifique-se de que realmente vai pingar na nossa conta no final do mês</p>
            </div>
        </div>
    </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent ({
    name: 'MotivacaoCompra'
})

</script>

<style scoped>
    .motivacao__motivos{
        width: 80%;
        display: flex;
        flex-direction: column;
        padding: 3rem;
        margin: 0 auto;
    }

    .motivos__um, .motivos__dois, .motivos__tres, .motivos__quatro{
        display: flex;
        flex-direction: row;
        justify-content: space-evenly;
        align-items: center;
        margin-bottom: 1em;
    }

    .um__numero, .dois__numero, .tres__numero, .quatro__numero{
        color: #00419E;
        font-size: 48px;
        font-weight: bold;
        margin-right: 2em;
    }

    .um__texto, .dois__texto, .tres__texto, .quatro__texto{
        color: #000;
        font-size: 19px;
        font-weight: 500;
        text-align: center;
    }
</style>