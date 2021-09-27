<template>
    <section class="section">
        <h1 class="title">Cadastro - Representante</h1>

        <section>
        <b-field label="Nome">
            <b-input v-model="nome"></b-input>
        </b-field>
       
        <b-field label="Senha"
            
            >
            <b-input value="johnsilver" maxlength="30"></b-input>
        </b-field>

        <b-field label="Password">
            <b-input type="password"
                value="iwantmytreasure"
                password-reveal>
            </b-input>
        </b-field>
      
    </section>
    </section>
</template>