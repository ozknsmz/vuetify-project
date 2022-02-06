<template>
  <v-app>
   <Admin/>
    <v-content class="ma-4">
      <router-view></router-view>
    </v-content>
  </v-app>
</template>

<script>
import Admin from '../src/components/Admin.vue'
export default {
  name: "App",

  components: {
    Admin,
  },

  data: () => ({
    //
  }),
};
</script>
