<template>
  <v-container>
    <v-flex class="text-right">
      <v-chip class="ma-2" outlined color="#023565" label text-color="#023565">
        <v-icon left> mdi-account-circle-outline </v-icon>
        {{ panel_active }}
      </v-chip>
    </v-flex>
    <v-divider class="mt-2"></v-divider>
    <v-layout
      class="overflow-y-auto pa-5 ma-0 ba-0"
      justify-center
      fill-height
      style="height: 450px"
    >
      <v-flex>
        <v-form @submit.prevent="add" class="">
          <v-layout class="">
            <v-flex xs6 class="">
              <v-text-field
                color="#023565"
                prepend-icon="mdi-bank"
                label="Nombre Empresa"
              ></v-text-field>
              <v-text-field
                color="#023565"
                prepend-icon="mdi-file-document"
                label="NIT"
              ></v-text-field>
            </v-flex>
            <v-flex xs6 class="ma-0 pa-0 ba-0">
              <v-sheet
                color="grey lighten-3"
                elevation="3"
                height="139"
                width="110"
                min-height="139"
                min-width="110"
                max-height="139"
                max-width="110"
                class="mx-auto"
              >
              </v-sheet>
            </v-flex>
          </v-layout>
          <v-layout>
            <v-flex xs6>
              <v-text-field
                prepend-icon="mdi-account-tie"
                color="#023565"
                label="Representante Legal"
              >
              </v-text-field>
            </v-flex>
            <v-flex xs6 class="pl-2">
              <v-text-field
                color="#023565"
                prepend-icon="mdi-card-account-details"
                label="Documento Representante"
              ></v-text-field>
            </v-flex>
          </v-layout>

          <v-layout>
            <v-flex xs6>
              <v-text-field
                color="#023565"
                prepend-icon="mdi-map-marker"
                label="Dirección Empresa"
              ></v-text-field>
            </v-flex>
            <v-flex xs6 class="pl-2">
              <v-text-field
                color="#023565"
                hint="Ej: Centro,Popayán,Cauca"
                prepend-icon="mdi-map-marker-outline"
                label="Localidad"
              ></v-text-field>
            </v-flex>
          </v-layout>
          <v-layout>
            <v-flex xs6>
              <v-text-field
                color="#023565"
                prepend-icon="mdi-phone-classic"
                label="Teléfono"
              ></v-text-field>
            </v-flex>
            <v-flex xs6 class="pl-2">
              <v-text-field
                color="#023565"
                prepend-icon="mdi-phone-dial-outline"
                label="Extensión"
              ></v-text-field>
            </v-flex>
          </v-layout>

          <v-layout>
            <v-flex xs6 class="pl-2">
              <v-text-field
                color="#023565"
                prepend-icon="mdi-mail"
                label="Correo Electrónico"
              ></v-text-field>
            </v-flex>
            <v-flex xs6 class="pl-2">
              <v-text-field
                color="#023565"
                prepend-icon="mdi-content-duplicate"
                label="Documentos Soporte"
              ></v-text-field>
            </v-flex>
          </v-layout>
        </v-form>
      </v-flex>
    </v-layout>

    <v-flex class="text-right pt-5 pr-5">
      <v-btn
        color="#023565"
        elevation="5"
        small
        class="mr-8 white--text"
        type="submit"
      >
        Agregar
      </v-btn>
      <v-btn color="grey" elevation="5" small type="submit"> Limpiar </v-btn>
    </v-flex>
  </v-container>
</template>

<script>
//import { mapState, mapMutations } from "vuex";
export default {
  name: "Person1",
  data() {
    return {
     
    };
  },
  
};
</script>


<style>
</style>