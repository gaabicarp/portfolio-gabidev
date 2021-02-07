<template>
    <b-navbar centered>
        <template #start>
            <b-navbar-item href="#">
                Home
            </b-navbar-item>
            <b-navbar-item href="#">
                Sobre mi
            </b-navbar-item>
            <b-navbar-item tag="router-link" :to="{ path: '/' }">
                <img
                    src="~/assets/img/logoblack.png"
                    alt="Logo - Gabidev - Desarrollo Web - Freelance"
                    style="max-height: 3.75em;"
                >
            </b-navbar-item>
            <b-navbar-item href="#">
                Mis proyectos
            </b-navbar-item>
            <b-navbar-item href="#">
                Contactame
            </b-navbar-item>
        </template>

        <template #end>

        </template>
    </b-navbar>
</template>

<style scoped>
    .navbar{
        margin-top: 1em;
    }

    .navbar-item{
        margin: 0em 1.5em;
    }
</style>