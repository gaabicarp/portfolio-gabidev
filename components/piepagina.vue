<template>
<div class="">

    <div class="foot">
        <div class="columns">
            <div class="column is-flex is-justify-content-center is-align-items-center">
                <div class="is-flex is-align-items-center img-container">
                    <b-navbar-item tag="router-link" :to="{ path: '/' }" id="logo-navbar">
                        <img
                            src="~/assets/img/logowhite.png"
                            alt="Logo - Gabidev - Desarrollo Web - Freelance"
                            style="max-height: 3.75em;"
                        >
                    </b-navbar-item>
                </div>
            </div>
            <div class="column link-container is-flex-direction-column is-justify-content-center is-align-items-center">
                <p>Inicio</p>
                <p>Sobre Mi</p>
                <p>Proyectos</p>
                <p>Contacto</p>
            </div>
            <div class="column is-flex is-justify-content-center is-align-items-center">
                <div class="columns mobile-flex">
                    <div class="column">
                        <div class="is-flex is-justify-content-center has-text-white">
                            <a href="http://www.github.com/gaabicarp" class="button is-ghost has-text-white" target="_blank">
                                <font-awesome-layers class="fa-2x">
                                    <font-awesome-icon :icon="faGithub"  />
                                </font-awesome-layers>
                            </a>
                        </div>
                    </div>
                    <div class="column">
                        <div class="is-flex is-justify-content-center has-text-white">
                            <a href="https://www.youtube.com/channel/UCltJTt4tErqKYXXbYbZ6S7A" class="button is-ghost has-text-white" target="_blank">
                                <font-awesome-layers class="fa-2x">
                                    <font-awesome-icon :icon="faYoutube"  />
                                </font-awesome-layers>
                            </a>
                        </div>
                    </div>
                    <div class="column">
                        <div class="is-flex is-justify-content-center has-text-white">
                            <a href="https://www.linkedin.com/in/gabrieljotallan/" class="button is-ghost has-text-white" target="_blank">
                                <font-awesome-layers class="fa-2x">
                                    <font-awesome-icon :icon="faLinkedin"  />
                                </font-awesome-layers>
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="copy">
        <p class="has-text-centered">Everything © <a href="/" class="has-text-white">Gabriel Jotallan</a> 2019</p>
    </div>
</div>
</template>

<script>
import {faGithub, faYoutube, faLinkedin} from '@fortawesome/free-brands-svg-icons';
export default {
    computed: {
        faGithub(){
            return faGithub;
        },
        faYoutube(){
            return faYoutube;
        },
        faLinkedin(){
            return faLinkedin;
        }
    }
}
</script>

<style lang="scss" scoped>
    .foot{
        background-color: #f71e1e;
        min-height: 8em;
        color: white;
    }

    .copy{
        background-color: #ac0e0e;
        color: white;
    }
    
    @media screen and (min-width: 1024px) {
        .link-container{
            display: flex;
        }
    }
    @media screen and (max-width: 1024px) {
        .mobile-flex{
            display: flex;
            margin-bottom: 0.5em;
        }
        .img-container{
            justify-content: center;
        }
        .link-container{
            display: none;
        }
    }
</style>