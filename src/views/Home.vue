<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <Titulo texto="Pagina de Inicio" />
  </div>
<h3>Brandon Yahir Flores Vazquez <br>
    Grupo: 3 A <br>
    Materia: Aplicaciones Web Orientadas a Servicios <br>
    Carrera: Tecnologias de la Informacion Desarrollo de Software Multiplataforma
    </h3>
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
h3 {
background-color: rgb(5, 253, 5);

margin: auto;

color: blue;
}
</style>