<template>
  <v-app>
  <SideBar />

    <v-main>
      <router-view/>
    </v-main>
  </v-app>
</template>

<script>
import sideBar from './components/sideBar.vue';

export default {
    name: "App",
    components: { sideBar, },
    data: () => ({
    //
    }),
    
};
</script>
