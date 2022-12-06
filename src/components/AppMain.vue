<script>
import SectionWelcome from './SectionWelcome.vue';
import SectionMeet from './SectionMeet.vue';
import SectionHealthService from './SectionHealthService.vue';
import SectionTour from './SectionTour.vue';
import SectionService from './SectionService.vue';
import SectionAppointment from './SectionAppointment.vue';
import SectionSlider from './SectionSlider.vue';







export default {
  name: 'AppMain',
  components:{
    SectionWelcome,
    SectionMeet,
    SectionHealthService,
    SectionTour,
    SectionService,
    SectionAppointment,
    SectionSlider,
}
}
</script>

<template>

  <SectionWelcome/>
  <SectionMeet/>
  <SectionHealthService/>
  <SectionTour/>
  <SectionService/>
  <SectionAppointment/>
  <SectionSlider/>









</template>

<style lang="scss" scoped>

</style>
