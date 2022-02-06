
<template>
 <v-app>
   <Navbar/>
   <v-content class="ma-4">
     <router-view></router-view>
   </v-content>
 </v-app>
</template>

<script>
import Navbar from "./components/Navbar.vue";

export default {
  name: "App",
  data() {
    return {};
  },
  components: {
    Navbar,
  },

};
</script>