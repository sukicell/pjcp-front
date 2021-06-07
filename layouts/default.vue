<template>
  <div>
    <v-app id="inspire">
      <Header />
      <Main />
      <!-- <Nuxt /> -->
    </v-app>
  </div>
</template>

<script>
import Header from './header.vue'
import Main from './main.vue'
export default {
  components: {
    Header,
    Main
  }
}
</script>
