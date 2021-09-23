<template>
  <q-layout view="lHh Lpr lFf">
    <NavbarT/>
    <FrontPage/>
    <AboutStellar/>
    <!-- <Metaverse/> -->
    <!-- <PersonalChar/> -->
    <!-- <CrossOver/> -->
    <ThreeSections/>
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
import NavbarT from 'src/components/NavbarT.vue'
import FrontPage from 'src/components/FrontPage.vue'
import AboutStellar from 'src/components/AboutStellar.vue'
// import Metaverse from 'src/components/Metaverse.vue'
// import PersonalChar from 'src/components/PersonalChar.vue'
// import CrossOver from 'src/components/CrossOver.vue'
import GameFeatures from 'src/components/GameFeatures.vue'
import TokenEcon from 'src/components/TokenEcon.vue'
import Roadmap from 'src/components/Roadmap.vue'
import OurTeam from 'src/components/OurTeam.vue'
import Advisors from 'src/components/Advisors.vue'
import Partners from 'src/components/Partners.vue'
import KeepTouch from 'src/components/KeepTouch.vue'
import Footer from 'src/components/Footer.vue'
import ThreeSections from 'src/components/ThreeSections.vue'

export default {
  components: { NavbarT, FrontPage, AboutStellar, GameFeatures, TokenEcon, Roadmap, OurTeam, Advisors, Partners, KeepTouch, Footer, ThreeSections },
  setup() {

  },
}
</script>