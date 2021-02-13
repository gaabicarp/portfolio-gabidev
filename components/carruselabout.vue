<template>
    <div class="container">
        <div class="columns my-6">
            <div class="column">
                <b-carousel>
                    <b-carousel-item v-for="(carousel, i) in carousels" :key="i">
                        <section :class="`hero is-medium is-${carousel.color}`">
                            <figure class="image is-16by9">
                                <img :src="AboutImg(carousel.img)">
                            </figure>
                        </section>
                    </b-carousel-item>
                </b-carousel>
            </div>
            <div class="column">
                <p class="title is-size-1 has-text-centered">
                    Gabriel Jotallan
                </p>
                <div class="has-text-centered">
                    <p class="has-text-centered">Mi primer contacto con la computadora fue gracias a los jueguitos. De ahi en adelante mi interes sobre la informatica empezo a crecer cada vez mas. Hoy en dia puedo dedicarme a la informatica y paso a paso voy creciendo y formando mi carrera profesional.</p>
                    <p class="has-text-centered">Actualmente estoy estudiando en la Universidad Nacional de San Martin, Buenos Aires, Argentina. Estoy terminando el segundo año de tres que dura la carrera. Luego de eso, tengo intenciones de apuntar a alguna ingenieria.</p>
                    <p></p>
                </div>
            </div>
        </div>
    </div>
</template>


<script>

export default {
    data(){
        return {
            carousels: [
                { text: 'Slide 1', color: 'primary', img: 'bogota'},
                { text: 'Slide 2', color: 'info', img: 'caribe'},
                { text: 'Slide 3', color: 'success', img: 'chile'},
                { text: 'Slide 4', color: 'warning', img: 'copacabana'},
                { text: 'Slide 5', color: 'danger', img: 'iruya'},
                { text: 'Slide 6', color: 'primary', img: 'machupichu'},
                { text: 'Slide 7', color: 'info', img: 'quilotoa'},
                { text: 'Slide 8', color: 'success', img: 'sanpedro'},
                { text: 'Slide 9', color: 'warning', img: 'sorata'}
            ]
        }
    },
    methods:{
        AboutImg(filename){
            return require(`../assets/img/personal/${filename}.jpg`)
        }
    }
}
</script>

<style lang="scss" scoped>
    .fa-layers{
        width: 2em;
    }
    figure img{
        object-fit: cover;
    }
</style>