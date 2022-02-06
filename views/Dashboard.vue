
<template>
  <div class="team">
    <h1 class="subheading grey--text">IN HERE, WILL BE DASHBOARD</h1>
    <v-container >

    </v-container>
  </div>
</template>

<script>
// @ is an alias to /src
export default {
  name: 'team',
  components: {
   
  },
  data : () => ({
    team: [
      {name: 'Iyad', role: 'web developer', avatar:'/img1.png'},
      {name: 'Reda', role: 'Graphic designer', avatar:'/img2.png'},
      {name: 'Zineb', role: 'web developer', avatar:'/img3.png'},
      {name: 'Hu TechGroup', role: 'Desktop developer', avatar:'/img4.png'},
    ]
  }),
}
</script>
