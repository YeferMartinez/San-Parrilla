<template>
  <v-footer dark padless>
    <v-card
      flat
      tile
      class="indigo lighten-1 white--text text-center"
    >
      <v-card-text>
        <v-btn icon href="https://es-la.facebook.com/" target="_blank">
          <v-icon size="24px">{{ "mdi-facebook" }}</v-icon>
        </v-btn>
        <v-btn icon href="https://twitter.com/?lang=es" target="_blank">
          <v-icon size="24px">{{ "mdi-twitter" }}</v-icon>
        </v-btn>
        <v-btn icon href="https://co.linkedin.com" target="_blank">
          <v-icon size="24px">{{ "mdi-linkedin" }}</v-icon>
        </v-btn>
        <v-btn icon href="https://www.instagram.com/?hl=es" target="_blank">
          <v-icon size="24px">{{ "mdi-instagram" }}</v-icon>
        </v-btn>
      </v-card-text>

      <v-card-text class="white--text pt-0">
        Phasellus feugiat arcu sapien, et iaculis ipsum elementum sit amet. Mauris cursus commodo interdum. Praesent ut risus eget metus luctus accumsan id ultrices nunc. Sed at orci sed massa consectetur dignissim a sit amet dui. Duis commodo vitae velit et faucibus. Morbi vehicula lacinia malesuada. Nulla placerat augue vel ipsum ultrices, cursus iaculis dui sollicitudin.algunas imagenes y descripciones tomadas de: https://www.esquire.com/es/donde-comer-beber/g27537724/carne-kobe-roja-cortes-ternera/
      </v-card-text>

      <v-divider></v-divider>

      <v-card-text class="white--text">
        {{ new Date().getFullYear() }} &copy; <strong>San Parrilla</strong>
      </v-card-text>
    </v-card>
  </v-footer>
</template>

<script>
  export default {
      name: 'Footer',
  }
</script>

<style>
    .v-sheet.v-footer:not(.v-sheet--outlined){
        padding-top: 100px;
        background: transparent;
    }
</style>