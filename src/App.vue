<template>
  <nav>
    <router-link to="/">Inicio</router-link> 
    <router-link to="/menu">Menu</router-link> 
    <router-link to="/pedido">Pedido</router-link>   
    <router-link to="/about">Acerca de </router-link>
  </nav>
  <router-view/>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
  font-size: 27px;
  background-color: #75c9c8;
  overflow: hidden;
  scroll-behavior: auto;
}

nav a {
  font-weight: bold;
  color: #f2f2f2;
  list-style: none;
  margin-left: 30px;
  left: 50px; 
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>


