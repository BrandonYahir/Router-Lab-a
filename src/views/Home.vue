<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <Titulo texto="Pagina de Inicio" />
    <p>Brandon Yahir Flores Vazquez <br>
       Grupo: 3 A <br>
       Materia: Aplicaciones Web Orientadas a Servicios <br>
       Carrera: Tecnologias de la Informacion Desarrollo de Software Multiplataforma
       </p>
  </div>
</template>

<script>
import Titulo from '../components/Titulo.vue'

export default {
  name: 'Home',
  components: {
    Titulo
  }
}
</script>

<style>
p {
background-color: rgb(5, 253, 5);

margin: auto;

color: blue;
}
</style>