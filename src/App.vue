<template>
  <div>
    <TheHeader></TheHeader>
    <TheBlackSection/>
    <TheBlueSection/>
    <TheBannerFooter/>
  </div>
</template>

<script>
import TheHeader from './components/TheHeader.vue'
import TheBlackSection from './components/TheBlackSection.vue'
import TheBlueSection from './components/TheBlueSection.vue'
import TheBannerFooter from './components/TheBannerFooter.vue'

export default {
  components: {
    TheHeader,
    TheBlackSection,
    TheBlueSection,
    TheBannerFooter
}
}
</script>

<style lang="scss">

</style>
