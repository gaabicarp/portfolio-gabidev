<template>
    <div class="container my-5">
        <p class="title is-size-1 has-text-centered">Mis proximos pasos</p>
        <div class="box">
            <p class="is-size-4 has-text-centered">Tecnologias que quiero aprender</p>
            <div class="columns">
                <div class="column">
                    <div class="is-flex is-flex-direction-column is-justify-content-center is-align-items-center m-5">
                        <font-awesome-layers class="fa-5x">
                            <font-awesome-icon :icon="faDocker"  />
                        </font-awesome-layers> 
                        <p>Docker</p>
                    </div>
                </div>
                <div class="column">
                </div>
                <div class="column">
                </div>
            </div>
        </div>



        <div class="padre">
            <div class="hijo">
                <p>hola</p>
            </div>
            <div class="hijo">
                <p>hola2</p>
            </div>
        </div>




    </div>
</template>

<script>
import {faCircle, faDotCircle} from '@fortawesome/free-solid-svg-icons';
import {faDocker} from '@fortawesome/free-brands-svg-icons'
export default {
    computed: {
        faDocker(){
            return faDocker;
        },
        faDotCircle(){
            return faDotCircle;
        }
    }
}
</script>

<style scoped>
    .padre{
        display: flex;
        flex-direction: row;
        justify-content: flex-start;
    }
</style>