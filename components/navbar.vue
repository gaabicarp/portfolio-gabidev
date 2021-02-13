<template>
    <div class="navbar-box">
        <b-navbar centered>
            <template #brand>
                <b-navbar-item tag="router-link" :to="{ path: '/' }" id="logo-navbar">
                    <img
                        src="~/assets/img/logoblack.png"
                        alt="Logo - Gabidev - Desarrollo Web - Freelance"
                        style="max-height: 3.75em;"
                    >
                </b-navbar-item>
            </template>
            <template #start>
                <b-navbar-item href="/">
                    Home
                </b-navbar-item>
                <b-navbar-item href="aboutme">
                    Sobre mi
                </b-navbar-item>
                <b-navbar-item tag="router-link" :to="{ path: '/' }" id="logo-menu">
                    <img
                        src="~/assets/img/logoblack.png"
                        alt="Logo - Gabidev - Desarrollo Web - Freelance"
                        style="max-height: 3.75em;"
                    >
                </b-navbar-item>
                <b-navbar-item href="portfolio">
                    Mis proyectos
                </b-navbar-item>
                <b-navbar-item href="contact">
                    Contactame
                </b-navbar-item>
            </template>

            <template #end>

            </template>
        </b-navbar>
    </div>
</template>

<style scoped>
    .navbar-box{
        border-radius: 6px;
        box-shadow: 0 0.5em 1em -0.125em rgb(10 10 10 / 10%), 0 0px 0 1px rgb(10 10 10 / 2%);
        color: #4a4a4a;
        margin-bottom: 1em;
    }

    .navbar-item{
        margin: 0em 1.5em;
    }

    @media screen and (max-width: 1024px) {
        #logo-menu{
            display: none;
        }
    }

    @media screen and (min-width: 1024px){
        #logo-navbar{
            display: none;
        }
    }

</style>