<template>
    <div>
        <h4 class="ajuda__titulo">Precisando de ajuda para se decidir?</h4>
        <p class="ajuda__subtitulo">Peça a ajuda de nossos especialistas e te ajudaremos você a se decidir entre alguns modelos ou até mesmo podemos sugerir alguns novos modelos de acordo com seus desejos e escolhas</p>
        <hr>
        <div class="ajuda__content">
            <div class="ajuda__cadastro">
                <label for="email">Insira abaixo o seu melhor Email</label>
                <input
                type="email"
                id="email"
                class="input-padrao"
                required
                placeholder="seumelhoremail@dominio.com"
                />
                <input class="enviar" type="submit" value="Solicitar Ajuda" />
            </div>
            <div class="ajuda__ilustracao">
                <img class="ilustracao" src="../assets/IMGs/ilustracoes/Ilustracao-Ajuda.png" alt="">
            </div>
        </div>
    </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent ({
    name: 'PrecisaAjuda'
})

</script>

<style scoped>
    .ajuda__content{
        display: flex;
        flex-direction: row;
        margin: 0 auto;
        width: 90%;
        align-items: center;
    }

    .ajuda__titulo{
        font-size: 35px;
    }

    .ajuda__cadastro, .ajuda__ilustracao{
        margin: 0 auto;
        text-align: center;
    }

    .ajuda__cadastro{
        display: flex;
        flex-direction: column;
    }

    label{
        font-size: 30px;
        color: #000;
        text-align: center;
        margin-bottom: 1em;
    }

    #email, .enviar{
        width: 400px;
        margin: 0 auto .4em auto;
        text-align: center;
        height: 50px;
        border-radius: 20px;
        border-color: #00419E;
        transition: 1s all;
    }

    .enviar:hover{
        background-color: #00419E;
        border-color: #000;
        color: #FDFDFD;
        transition: 1s all;
    }

    .ilustracao{
        height: 500px;
        width: 500px;
        object-fit: cover;
    }
</style>