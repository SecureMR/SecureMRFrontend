<template>
<img class="logo" src="../assets/secure-mr-logo.png"/>
<h1>Login</h1>
<div class="login">
<input type="text" v-model="email" placeholder="Tú correo electrónico"/>
<button v-on:click="loginPassword">Iniciar Sesión con Contraseña</button>
<button v-on:click="loginBiometry">Iniciar Sesión con Biometría</button>
<button v-on:click="login">Login</button>
<p>
<router-link to="Home">Login</router-link>
</p>
</div>
</template>
<script>
export default{
name: 'Login'
}
</script>