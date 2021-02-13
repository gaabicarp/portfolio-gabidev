<template>
    <div class="container mb-5">
        <div class="columns">
            <div class="column is-one-third">
                <p class="is-size-3 has-text-centered mb-5">Habilidades Blandas</p>
                <div class="box h-93">
                    <div class="is-flex is-flex-direction-row is-justify-content-center	is-align-items-center">
                        <div class="is-flex is-justify-content-center is-align-items-center">
                            <figure class="image is-96x96">
                                <img src="~/assets/icon/habilidades.svg">
                            </figure>
                        </div>
                        <div class="is-flex is-flex-direction-column is-justify-content-center ml-3">
                            <p class="is-size-4 has-text-weight-bold">Proactivo:</p>
                            <p class="">No hace falta que estes atras mio diciendome que hacer. Tomo la iniciativa y pongo toda mi predisposicion para sacar los proyectos adelante.</p>
                        </div>
                    </div>
                    <div class="is-flex is-flex-direction-row is-justify-content-center	is-align-items-center mt-5">
                        <div class="is-flex is-justify-content-center is-align-items-center">
                            <figure class="image is-96x96">
                                <img src="~/assets/icon/idea.svg">
                            </figure>
                        </div>
                        <div class="is-flex is-flex-direction-column is-justify-content-center ml-3">
                            <p class="is-size-4 has-text-weight-bold">Creativo:</p>
                            <p class="">No todo es copiar y pegar en esta vida. No voy a ponerme a reinventar la rueda, pero siempre le pongo mi sello creativo a lo que hago.</p>
                        </div>
                    </div>
                    <div class="is-flex is-flex-direction-row is-justify-content-center	is-align-items-center mt-5">
                        <div class="is-flex is-justify-content-center is-align-items-center">
                            <figure class="image is-96x96">
                                <img src="~/assets/icon/pregunta.svg">
                            </figure>
                        </div>
                        <div class="is-flex is-flex-direction-column is-justify-content-center ml-3">
                            <p class="is-size-4 has-text-weight-bold">Curioso:</p>
                            <p class="">Siempre con el buscador en la mano. No me gusta quedarme con la duda de nada, me gusta aprender como funciona el mundo y todo lo que lo compone.</p>
                        </div>
                    </div>
                    <div class="is-flex is-flex-direction-row is-justify-content-center	is-align-items-center mt-5">
                        <div class="is-flex is-justify-content-center is-align-items-center">
                            <figure class="image is-96x96">
                                <img src="~/assets/icon/rompecabezas.svg">
                            </figure>
                        </div>
                        <div class="is-flex is-flex-direction-column is-justify-content-center ml-3">
                            <p class="is-size-4 has-text-weight-bold">Resiliente:</p>
                            <p class="">Me gustan los desafios ya que afrontarlos siempre supone nuevos aprendizajes. Poder mantener la calma es la clave para solucionar cualquier conflicto.</p>
                        </div>
                    </div>
                    <div class="is-flex is-flex-direction-row is-justify-content-center	is-align-items-center mt-5">
                        <div class="is-flex is-justify-content-center is-align-items-center">
                            <figure class="image is-96x96">
                                <img src="~/assets/icon/reunion.svg">
                            </figure>
                        </div>
                        <div class="is-flex is-flex-direction-column is-justify-content-center ml-3">
                            <p class="is-size-4 has-text-weight-bold">Compañerismo:</p>
                            <p class="">La comunicacion es la clave, intento siempre ser claro en mis ideas. Estoy dispuesto a ayudar a los demas y escuchar las criticas cuando es necesario.</p>
                        </div>
                    </div>
                    <div class="is-flex is-flex-direction-row is-justify-content-center	is-align-items-center mt-5">
                        <div class="is-flex is-justify-content-center is-align-items-center	">
                            <figure class="image is-96x96">
                                <img src="~/assets/icon/agil.svg">
                            </figure>
                        </div>
                        <div class="is-flex is-flex-direction-column is-justify-content-center ml-3">
                            <p class="is-size-4 has-text-weight-bold">Agil:</p>
                            <p class="">Trabajo con metodologias agiles. El cliente siempre esta en contacto con el producto dando su validacion y feedback constantemente.</p>
                        </div>
                    </div>
                </div>
            </div>
            <div class="column">
                <p class="is-size-3 has-text-centered mb-5">Habilidades Tecnicas</p>
                <div class="is-flex is-flex-direction-column is-justify-content-space-between h-93">
                    <div class="box">
                        <p class="is-size-4 has-text-centered has-text-weight-bold mb-4">Front-End:</p>
                        <div class="columns mobile-flex">
                            <div class="column">
                                <div class="is-flex is-justify-content-center has-text-primary">
                                    <font-awesome-layers class="fa-5x">
                                        <font-awesome-icon :icon="faAngular"  />
                                    </font-awesome-layers>
                                </div>
                                <p class="is-size-4 has-text-centered">Angular</p>
                            </div>
                            <div class="column">
                                <div class="is-flex is-justify-content-center has-text-info">
                                    <font-awesome-layers class="fa-5x">
                                        <font-awesome-icon :icon="faReact"  />
                                    </font-awesome-layers>
                                </div>
                                <p class="is-size-4 has-text-centered">React</p>
                            </div>
                            <div class="column">
                                <div class="is-flex is-justify-content-center has-text-success">
                                    <font-awesome-layers class="fa-5x">
                                        <font-awesome-icon :icon="faVuejs"  />
                                    </font-awesome-layers>
                                </div>
                                <p class="is-size-4 has-text-centered">Vue</p>
                            </div>
                        </div>
                    </div>
                    <div class="box">
                        <p class="is-size-4 has-text-centered has-text-weight-bold mb-4">CSS-Frameworks:</p>
                        <div class="columns mobile-flex">
                            <div class="column">
                                <div class="is-flex is-justify-content-center has-text-link">
                                    <font-awesome-layers class="fa-5x">
                                        <font-awesome-icon :icon="faBootstrap"  />
                                    </font-awesome-layers>
                                </div>
                                <p class="is-size-4 has-text-centered">Bootstrap</p>
                            </div>
                            <div class="column">
                                <div class="is-flex is-justify-content-center is-align-items-center">
                                    <figure class="image is-64x64">
                                        <img src="~/assets/icon/angular-material-logo.svg">
                                    </figure>
                                </div>
                                <p class="is-size-4 has-text-centered">Angular Material</p>
                            </div>
                            <div class="column">
                                <div class="is-flex is-justify-content-center is-align-items-center">
                                    <figure class="image is-64x64">
                                        <img src="~/assets/icon/bulma-logo.svg">
                                    </figure>
                                </div>
                                <p class="is-size-4 has-text-centered">Bulma</p>
                            </div>
                        </div>
                    </div>
                    <div class="box">
                        <p class="is-size-4 has-text-centered has-text-weight-bold mb-4">Back-End:</p>
                        <div class="columns mobile-flex">
                            <div class="column">
                                <div class="is-flex is-justify-content-center has-text-success">
                                    <font-awesome-layers class="fa-5x">
                                        <font-awesome-icon :icon="faNodeJs"  />
                                    </font-awesome-layers>
                                </div>
                                <p class="is-size-4 has-text-centered">Node.js</p>
                            </div>
                            <div class="column">
                                <div class="is-flex is-justify-content-center is-align-items-center">
                                    <figure class="image is-64x64">
                                        <img src="~/assets/icon/mongodb.svg">
                                    </figure>
                                </div>
                                <p class="is-size-4 has-text-centered">MongoDB</p>
                            </div>
                            <div class="column">
                                <div class="is-flex is-justify-content-center is-align-items-center">
                                    <figure class="image is-64x64">
                                        <img src="~/assets/img/sql-server.png">
                                    </figure>
                                </div>
                                <p class="is-size-4 has-text-centered">Sql Server</p>
                            </div>
                        </div>
                    </div>
                    <div class="box">
                        <p class="is-size-4 has-text-centered has-text-weight-bold mb-4">Otros:</p>
                        <div class="columns mobile-flex">
                            <div class="column">
                                <div class="is-flex is-justify-content-center has-text-orange">
                                    <font-awesome-layers class="fa-5x">
                                        <font-awesome-icon :icon="faGitAlt"  />
                                    </font-awesome-layers>
                                </div>
                                <p class="is-size-4 has-text-centered">Git</p>
                            </div>
                            <div class="column">
                                <div class="is-flex is-justify-content-center">
                                    <font-awesome-layers class="fa-5x">
                                        <font-awesome-icon :icon="faLinux"  />
                                    </font-awesome-layers>
                                </div>
                                <p class="is-size-4 has-text-centered">Linux</p>
                            </div>
                            <div class="column">
                                <div class="is-flex is-justify-content-center has-text-info">
                                    <font-awesome-layers class="fa-5x">
                                        <font-awesome-icon :icon="faDocker"  />
                                    </font-awesome-layers>
                                </div>
                                <p class="is-size-4 has-text-centered">Docker</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="has-text-centered my-6">
            <b-button type="is-primary" size="is-medium">
                Descargar CV
            </b-button>
        </div>
    </div>
</template>

<script>
import {faAngular, faHtml5, faCss3, faJsSquare, faReact, faVuejs, faBootstrap, faNodeJs, faGitAlt, faLinux, faDocker} from '@fortawesome/free-brands-svg-icons';
export default {
    computed: {
        faAngular(){
            return faAngular;
        },
        faHtml5(){
            return faHtml5;
        },
        faCss3(){
            return faCss3;
        },
        faJsSquare(){
            return faJsSquare;
        },
        faReact(){
            return faReact;
        },
        faVuejs(){
            return faVuejs;
        },
        faBootstrap(){
            return faBootstrap;
        },
        faNodeJs(){
            return faNodeJs;
        },
        faGitAlt(){
            return faGitAlt;
        },
        faLinux(){
            return faLinux;
        },
        faDocker(){
            return faDocker;
        }
    }
}
</script>

<style scoped>

    .has-text-orange{
        color: orangered;
    }

    @media screen and (max-width: 1024px) {
        .box{
            margin: 1em;
        }
        .mobile-flex{
            display: flex;
        }
    }

    .h-93{
        height: 93%;
    }
</style>