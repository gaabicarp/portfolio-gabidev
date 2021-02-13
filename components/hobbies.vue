<template>
    <div class="container">

        <div class="my-6">
            <p class="title has-size-1 has-text-centered">Mis Hobbies</p>
            <div class="box">
                <div class="columns">
                    <div class="column">
                        <div class="is-flex is-flex-direction-column is-justify-content-center is-align-items-center m-5">
                            <font-awesome-layers class="fa-7x has-text-success">
                                <font-awesome-icon :icon="faGamepad"  />
                            </font-awesome-layers>
                            <p class="has-text-weight-bold is-size-4 my-4">Jugar videojuegos</p>
                            <p class="has-text-centered">Me encantan los videojuegos, desde chico jugando a al FamilyGame, Playstation y ahora PC Master Race. Gran parte de mi sueldo va destinado a comprar juegos y componentes de pc, como todo buen gamer.</p>
                            <div class="is-flex is-justify-content-center is-align-items-center">
                                <p class="my-5">Si queres jugar conmigo agregame: </p>
                                <a href="https://www.steamcommunity.com/profiles/76561198114571345" class="button is-white" target="_blank">
                                    <font-awesome-layers class="fa-2x">
                                        <font-awesome-icon :icon="faSteam"  />
                                    </font-awesome-layers> 
                                </a>
                            </div>
                        </div>
                    </div>
                    <div class="column">
                        <div class="is-flex is-flex-direction-column is-justify-content-center is-align-items-center m-5">
                            <font-awesome-layers class="fa-7x has-text-primary">
                                <font-awesome-icon :icon="faGlobeAmericas"  />
                            </font-awesome-layers>
                            <p class="has-text-weight-bold is-size-4 my-4">Viajar por el mundo</p>
                            <p class="has-text-centered">Viajar es otra de mis grandes pasiones, recorri 2 veces latinoamerica como mochilero. La perimera vez duante 10 meses, la segunda durante anio y medio. Trabajando de artesano, musico y malabarista entre otras cosas.</p>
                            <div class="is-flex is-justify-content-center is-align-items-center">
                                <p class="my-5">Conoce mas sobre mi viaje: </p>
                                <a href="https://www.instagram.com/atrapadosenlibertad_/" class="button is-white" target="_blank">
                                    <font-awesome-layers class="fa-2x">
                                        <font-awesome-icon :icon="faInstagram"  />
                                    </font-awesome-layers> 
                                </a>
                            </div>
                        </div>
                    </div>
                    <div class="column">
                        <div class="is-flex is-flex-direction-column is-justify-content-center is-align-items-center m-5">
                            <font-awesome-layers class="fa-7x has-text-success">
                                <font-awesome-icon :icon="faGuitar"  />
                            </font-awesome-layers>
                            <p class="has-text-weight-bold is-size-4 my-4">Hacer Musica</p>
                            <p class="has-text-centered">Desde los 12 años que toco la guitarra de forma autodidacta, aprendi a tocar tambien la armonica y melodica. No soy buen cantante pero me defiendo. Viajando me subia a colectivos y restaurante a tocar canciones a la gorra.</p>
                            <div class="is-flex is-justify-content-center is-align-items-center">
                                <p class="my-5">Escucha algunas canciones caseras: </p>
                                <a href="https://www.youtube.com/playlist?list=PL95_pcdpOfGurR97PSBP6gro5ovgAXJqB" class="button is-white" target="_blank">
                                    <font-awesome-layers class="fa-2x">
                                        <font-awesome-icon :icon="faYoutube"  />
                                    </font-awesome-layers> 
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
import {faSteam, faInstagram, faYoutube} from '@fortawesome/free-brands-svg-icons';
import {faGamepad, faGlobeAmericas, faGuitar} from '@fortawesome/free-solid-svg-icons';
export default {
    computed: {
        faGamepad(){
            return faGamepad;
        },
        faGlobeAmericas(){
            return faGlobeAmericas;
        },
        faGuitar(){
            return faGuitar;
        },
        faSteam(){
            return faSteam;
        },
        faInstagram(){
            return faInstagram;
        },
        faYoutube(){
            return faYoutube;
        }
    }
}
</script>