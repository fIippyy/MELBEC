<!-- layouts/default.vue -->
<template>
  <v-app>
    <!-- Barra de Navegación Compartida -->
    <v-app-bar flat app>
      <v-spacer></v-spacer>
      <nuxt-link to="/nosaltres">
        <v-btn text class="nav-button">NOSALTRES</v-btn>
      </nuxt-link>
      <nuxt-link to="/tenda">
        <v-btn text class="nav-button">TENDA</v-btn>
      </nuxt-link>
      <nuxt-link to="/contacte">
        <v-btn text class="nav-button">CONTACTE</v-btn>
      </nuxt-link>
      <v-spacer></v-spacer>
      <v-toolbar-title class="logo-title">MELBEC</v-toolbar-title>
      <v-spacer></v-spacer>
      <v-text-field
        flat
        solo-inverted
        hide-details
        prepend-inner-icon="mdi-magnify"
        placeholder="Cerca..."
      ></v-text-field>
      <nuxt-link to="/inicia-sessio">
        <v-btn text class="nav-button">INICIA SESSIÓ</v-btn>
      </nuxt-link>
    </v-app-bar>

    <!-- Contenido de la Página -->
    <nuxt />
  </v-app>
</template>

<script>
export default {
  name: 'DefaultLayout',
};
</script>

<style scoped>
.nav-button {
  color: white;
  font-weight: bold;
}

.logo-title {
  color: white;
  font-size: 24px;
  font-weight: bold;
}
</style>
