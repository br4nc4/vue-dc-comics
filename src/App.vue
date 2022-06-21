<template>
  <div>
    <TheHeader></TheHeader>
    <TheBlackSection/>
    <TheBlueSection/>
  </div>
</template>

<script>
import TheHeader from './components/TheHeader.vue'
import TheBlackSection from './components/TheBlackSection.vue'
import TheBlueSection from './components/TheBlueSection.vue'

export default {
  components: {
    TheHeader,
    TheBlackSection,
    TheBlueSection
}
}
</script>

<style lang="scss">

</style>
