<template>
    <v-container>
      <h1 class="my-5">Inicia Sessiò</h1>
      <v-form>
        <v-text-field label="Usuari" required></v-text-field>
        <v-text-field label="Contrasenya" type="password" required></v-text-field>
        <v-btn color="primary">Entrar</v-btn>
      </v-form>
    </v-container>
  </template>
  
  <script>
  export default {
    name: 'IniciaSessioPage',
  };
  </script>
  
  <style scoped>
  /* Tus estilos aquí */
  </style>
  