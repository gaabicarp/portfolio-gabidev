<template>
<div class="container">
    <div class="box my-6">
        <div class="columns">
            <div class="column is-one-third">
                <figure class="image perfil">
                    <img class="is-rounded" src="~/assets/img/imagen-perfil.jpg" alt="Gabriel Jotallan - Desarrollador Web Fullstack - Gabidev">
                </figure>
            </div>
            <div class="column text-container">
                <div class="mt-6">
                    <h1 class="title is-1 has-text-centered">Bienvenido, soy Gabriel Jotallan.</h1>
                </div>
                <div class="has-text-centered mensaje">
                    <p>Soy desarrollador web fullstack. Tengo 27 años y soy estudiante de programacion en la UNSAM, Buenos Aires, Argentina. Me encantan los desafios y estar en constante aprendizaje. Si queres trabajar conmigo no dudes en contactarme.</p>
                </div>
                <div class="has-text-centered mt-5">
                    <div class="columns">
                        <div class="column">
                            <a class="button is-primary is-medium" href="/aboutme">
                                Mas Sobre Mi
                            </a>
                        </div>
                        <!-- <div class="column">
                            <b-button type="is-primary">
                                Descargar CV
                                <font-awesome-icon :icon="faFile" />
                            </b-button>
                        </div> -->
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="my-6">
        <p class="title is-1 has-text-centered">¿Que puedo ofrecerte?</p>
        <div class="columns mt-5">
            <div class="column">
                <div class="is-flex is-justify-content-center has-text-info mb-5">
                    <font-awesome-layers class="fa-5x">
                        <font-awesome-icon :icon="faPalette"  />
                    </font-awesome-layers>
                </div>
                <div class="p-4">
                    <p class="is-size-4 has-text-centered mb-4">Diseño y desarrollo de tu propuesta.</p>
                    <p class="has-text-centered">Hace realidad tu propuesta, desde un sitio web para tu emprendimiento hasta una web app. Te puedo guiar para juntos obtener un producto viable y desarrollado con las mejores tecnologias del mercado.</p>
                </div>
            </div>
            <div class="column">
                <div class="is-flex is-justify-content-center has-text-success mb-5">
                    <font-awesome-layers class="fa-5x">
                        <font-awesome-icon :icon="faRocket"  />
                    </font-awesome-layers>
                </div>
                <div class="p-4">
                    <p class="is-size-4 has-text-centered mb-4">Deployment y mantenimiento.</p>
                    <p class="has-text-centered">De nada sirve tener tu pagina si no tiene donde hospedarse. Quedate tranquilo que yo me ocupo del hosting, domino y mantenimiento de tu web para que no te tengas que ocupar de nada mas.</p>
                </div>
            </div>
            <div class="column">
                <div class="is-flex is-justify-content-center has-text-primary mb-5">
                    <font-awesome-layers class="fa-5x">
                        <font-awesome-icon :icon="faBullseye"  />
                    </font-awesome-layers>
                </div>
                <div class="p-4">
                    <p class="is-size-4 has-text-centered mb-4">Posicionamiento SEO.</p>
                    <p class="has-text-centered">¿Hay que hacer crecer ese embudo de ventas? No hay problema, te ayudo a generar visibilidad de tu web aplicando las mejores tecnicas para un buen posicionamiento en los principales buscadores web.</p>
                </div>
            </div>
        </div>
        <div class="has-text-centered">
            <a class="button is-success is-medium" href="/contact">
                Contactame
            </a>
        </div>
    </div>
</div>
</template>

<script>

import {faWhatsapp} from '@fortawesome/free-brands-svg-icons';
import {faFile, faPalette, faRocket, faBullseye} from '@fortawesome/free-solid-svg-icons';
export default {
    computed: {
        faWhatsapp(){
            return faWhatsapp;
        },
        faFile(){
            return faFile;
        },
        faPalette(){
            return faPalette;
        },
        faRocket(){
            return faRocket;
        },
        faBullseye(){
            return faBullseye;
        }
    }
}
</script>

<style scoped>
    .perfil{
        width: 20em;
        margin: auto;
    }

    .container{
        margin-bottom: 2em;
    }

    .text-container{
        display: flex;
        flex-direction: column;
        justify-content: space-around;
    }

    @media screen and (max-width: 1024px) {
        .box{
            margin: 1em;
        }

        .mensaje{
            margin-top: 0.5em;
        }

    }
</style>