<template>
  <v-app>
    <Nav />
    <v-main>
      <router-view>
      </router-view>
    </v-main>

  </v-app>
</template>

<script>
import Nav from '@/components/Nav'

export default {
  name: 'App',

  components: {
    Nav
  },

  data: () => ({
    //
  }),
};
</script>

<style scoped>
.dark {
  background-color: black;
}
</style>
