<template>
  <v-container>
    <v-layout
      class="overflow-y-auto pa-0 ma-5 ba-0"
      justify-center
      fill-height
      style="height: 450px"
    >
      <v-flex>
        <v-text-field
          color="#023065"
          prepend-icon="mdi-bank"
          label="Nombre Empresa"
        ></v-text-field>
      </v-flex>
      <v-flex>
        <v-text-field
          color="#023065"
          prepend-icon="mdi-bank"
          label="Nombre Empresa"
        ></v-text-field>
      </v-flex>
    </v-layout>
  </v-container>
</template>

<script> 
  import miSaludo from "../components/miSaludo";
  
  export default {
    name: 'miSaludo',

    data() {
    return {
     
    };
  },
 
  }
</script>
