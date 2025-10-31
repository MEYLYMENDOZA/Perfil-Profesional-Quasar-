<template>
  <div class="sidebar-bg text-white q-pa-xl">
    
    <q-avatar size="150px" class="q-mb-md sidebar-avatar">
      <img :src="fotoUrl" alt="Meyly Mendoza Cobeñas" />
    </q-avatar>

    <p class="text-subtitle2 q-mt-md">
      Estudiante de 7mo ciclo de Ingeniería de Tecnología de la Información y Sistemas en la Universidad ESAN. Con
      conocimientos en desarrollo web utilizando .NET Core, PostgreSQL y Git, y en análisis de datos con Power BI, Excel
      intermedio y SQL Server. Me caracterizo por ser detallista, organizada y colaborativa, con enfoque en la
      optimización de procesos y precisión en los resultados.
    </p>

    <div class="q-mt-xl">
      <div class="text-h6 text-weight-bold q-mb-sm">Contacto</div>
      <q-list dense class="text-white">
        <q-item>
          <q-item-section avatar><q-icon name="call" /></q-item-section>
          <q-item-section>Celular: 976580583</q-item-section>
        </q-item>
        <q-item>
          <q-item-section avatar><q-icon name="mail" /></q-item-section>
          <q-item-section>Correo: meylymendozaxo@gmail.com</q-item-section>
        </q-item>
        <q-item clickable tag="a" href="https://www.linkedin.com/in/meyly-mendoza-cobeñas" target="_blank">
          <q-item-section avatar><q-icon name="mdi-linkedin" /></q-item-section>
          <q-item-section>LinkedIn</q-item-section>
        </q-item>
      </q-list>
    </div>

    <div class="q-mt-xl">
      <div class="text-h6 text-weight-bold q-mb-sm">Educación</div>
      <p class="text-weight-medium q-mb-none">ESAN University</p>
      <p class="text-caption q-mb-none">Estudiante de Ingeniería de Tecnología de la Información y Sistemas</p>
      <p class="text-caption">Periodo: 2022 – Actualidad</p>
    </div>
  </div>
</template>

<script setup>
import fotoUrl from '../assets/mifoto.jpeg'; // **IMPORTANTE: Usa la ruta relativa que funcionó**
</script>

<style scoped>
.sidebar-bg {
  background-color: #55779B; /* Color azul similar al CV */
  min-height: 100vh;
}
.sidebar-avatar {
  border: 4px solid rgba(255, 255, 255, 0.5); /* Borde blanco semi-transparente */
}
</style>