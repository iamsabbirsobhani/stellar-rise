<template>
  <q-layout view="lHh Lpr lFf">
    <Navbar/>
    <FrontPage/>
    <AboutWarena/>
    <Metaverse/>
    <PersonalChar/>
    <CrossOver/>
    <GameFeatures/>
    <TokenEcon/>
    <Roadmap/>
    <OurTeam/>
    <Advisors/>
    <Partners/>
    <KeepTouch/>
    <Footer/>
    <q-page-container>
      <router-view />
    </q-page-container>
  </q-layout>
</template>


<script>
import Navbar from 'src/components/Navbar.vue'
import FrontPage from 'src/components/FrontPage.vue'
import AboutWarena from 'src/components/AboutWarena.vue'
import Metaverse from 'src/components/Metaverse.vue'
import PersonalChar from 'src/components/PersonalChar.vue'
import CrossOver from 'src/components/CrossOver.vue'
import GameFeatures from 'src/components/GameFeatures.vue'
import TokenEcon from 'src/components/TokenEcon.vue'
import Roadmap from 'src/components/Roadmap.vue'
import OurTeam from 'src/components/OurTeam.vue'
import Advisors from 'src/components/Advisors.vue'
import Partners from 'src/components/Partners.vue'
import KeepTouch from 'src/components/KeepTouch.vue'
import Footer from 'src/components/Footer.vue'

export default {
  components: { Navbar, FrontPage, AboutWarena, Metaverse, PersonalChar, CrossOver, GameFeatures, TokenEcon, Roadmap, OurTeam, Advisors, Partners, KeepTouch, Footer },
  setup() {

  },
}
</script>