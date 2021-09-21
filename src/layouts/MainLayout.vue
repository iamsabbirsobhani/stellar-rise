<template>
  <q-layout view="lHh Lpr lFf">
    <Navbar/>
    <FrontPage/>
    <q-page-container>
      <router-view />
    </q-page-container>
  </q-layout>
</template>


<script>
import Navbar from 'src/components/Navbar.vue'
import FrontPage from 'src/components/FrontPage.vue'

export default {
  components: { Navbar, FrontPage },
  setup() {

  },
}
</script>