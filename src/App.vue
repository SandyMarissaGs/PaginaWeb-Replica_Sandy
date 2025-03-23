<script setup>

import BarrraDeNavegacion from './components/BarrraDeNavegacion.vue';
import Descripcion from './components/Descripcion.vue';
import Carrusel from './components/Carrusel.vue';
import PieDePagina from './components/PieDePagina.vue';
</script>

<template>
  <div>
    <BarrraDeNavegacion/>
  </div>
  <div>
    <Descripcion/>
  </div>
  <div>
    <Carrusel/>
  </div>
  <div>
    <PieDePagina/>
  </div>
  
  <HelloWorld msg="Vite + Vue" />
</template>

<style scoped>

</style>
