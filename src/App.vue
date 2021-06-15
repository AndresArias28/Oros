<template>
  <v-app>
    <v-main>
      <router-view />
    </v-main>
    <v-footer id="pie" xs-10 class="justify-center" padless>
      <v-card-text class="dark--text text-center">
        <strong>
          Universidad del Cauca | Vicerrectoría Administrativa |
          SOLEMDev</strong
        >
        — {{ new Date().getFullYear() }}
      </v-card-text>
    </v-footer>
  </v-app>
</template>

<script>
export default {
  name: "App",

  data: () => ({
    //
  }),
};
</script>
