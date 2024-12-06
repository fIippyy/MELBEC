<template>
  <v-app>
    <v-container fluid class="pa-0">
      <!-- Background Image Section -->
      <div class="hero-section">
        <v-row>
          <v-col class="text-center">
            <!-- Navigation Bar -->
            <v-app-bar flat app>
              <v-spacer></v-spacer>
              <v-btn text class="nav-button" to="/nosaltres">NOSALTRES</v-btn>
              <v-btn text class="nav-button" to="/tenda">TENDA</v-btn>
              <v-btn text class="nav-button" to="/contacte">CONTACTE</v-btn>
              <v-spacer></v-spacer>
              <v-toolbar-title class="logo-title">MELBEC</v-toolbar-title>
              <v-spacer></v-spacer>
              <v-text-field flat solo-inverted hide-details prepend-inner-icon="mdi-magnify" placeholder="Cerca..."></v-text-field>
              <v-btn text class="nav-button" to="/inicia-sessio">INICIA SESSIÓ</v-btn>
            </v-app-bar>
          </v-col>
        </v-row>

        <!-- Main Content -->
        <v-row class="justify-center text-center main-content">
          <v-col>
            <h2 class="white--text">Descobreix el sabor mil·lenari de l'hidromel artesanal amb <strong>MELBEC</strong>.</h2>
          </v-col>
        </v-row>
      </div>
    </v-container>
  </v-app>
</template>

<script>
export default {
  name: 'MelbecLandingPage',
};
</script>

<style scoped>
.hero-section {
  background-image: url('background-image.jpg'); /* Cambia esto por la imagen de fondo que necesitas */
  background-size: cover;
  background-position: center;
  height: 100vh;
  position: relative;
}

.main-content {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}

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
