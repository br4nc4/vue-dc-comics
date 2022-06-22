<template>
  <div>
    <TheHeader></TheHeader>
    <TheJumbotronSection/>
    <TheBlackSection/>
    <TheBlueSection/>
    <TheBannerFooter/>
    <TheFooter/>
  </div>
</template>

<script>
import TheHeader from './components/TheHeader.vue'
import TheBlackSection from './components/TheBlackSection.vue'
import TheBlueSection from './components/TheBlueSection.vue'
import TheBannerFooter from './components/TheBannerFooter.vue'
import TheFooter from './components/TheFooter.vue'
import TheJumbotronSection from './components/TheJumbotronSection.vue'

export default {
  components: {
    TheHeader,
    TheBlackSection,
    TheBlueSection,
    TheBannerFooter,
    TheFooter,
    TheJumbotronSection
}
}
</script>

<style lang="scss">
@import "./assets/main.scss"
</style>
