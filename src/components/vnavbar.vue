<template>
    <b-navbar>
        <template #brand>
            <b-navbar-item tag="router-link" :to="{ path: '/' }">
                <img
                    src="https://raw.githubusercontent.com/buefy/buefy/dev/static/img/buefy-logo.png"
                    alt="Lightweight UI components for Vue.js based on Bulma"
                >
            </b-navbar-item>
        </template>
        <template #start>
            <b-navbar-item href="#/">
                Página Inicial
            </b-navbar-item>
            <b-navbar-item href="#/contato">
                Contato
            </b-navbar-item>
            <b-navbar-item href="#/cadastro">
                Cadastro
            </b-navbar-item>
        </template>
    </b-navbar>
    
</template>