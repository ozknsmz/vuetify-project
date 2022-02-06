<template>
  <v-footer
    dark
    padless
    app
    inset
    
  >
    <v-card
      class="flex"
      flat
      tile
      color="blue"
      :elevation="10"
    >

      <v-card-text class="py-1 white--text text-center">
        {{ new Date().getFullYear() }}
      </v-card-text>
    </v-card>
  </v-footer>
</template>

<style scoped>
.border {
  border-left: 4px solid #0ba518;
}
</style>