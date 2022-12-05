<script>
import SectionWelcome from './SectionWelcome.vue';
import SectionMeet from './SectionMeet.vue';
import SectionHealthService from './SectionHealthService.vue';
import SectionTour from './SectionTour.vue';
import SectionService from './SectionService.vue';






export default {
  name: 'AppMain',
  components:{
    SectionWelcome,
    SectionMeet,
    SectionHealthService,
    SectionTour,
    SectionService,

    
}
}
</script>

<template>

  <SectionWelcome/>
  <SectionMeet/>
  <SectionHealthService/>
  <SectionTour/>
  <SectionService/>







</template>

<style lang="scss" scoped>

</style>
