<template>
    <SideBar app></SideBar>
  <v-app>
    <v-main>

      <div class="content">
        <!-- Contenido de DefaultView aquí -->
        <default-view />
      </div>
    </v-main>
  </v-app>
</template>

<style scoped>
.content {
  margin-left: 300px; /* Ajusta el valor según el ancho de tu SideBar */
}
</style>

<script setup>
import SideBar from '@/components/Barra.vue'
import DefaultView from './View.vue'
</script>
