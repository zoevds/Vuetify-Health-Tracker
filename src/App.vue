<template>
  <v-app>
  <sideBar />

    <v-main>
      <router-view></router-view>
    </v-main>
  </v-app>
</template>

<script>
import sideBar from './/components/sideBar.vue';

export default {
    name: "App",
    components: { sideBar, },
    data: () => ({
    //
    }),
    
};
</script>
