<template>
  <div>
    <slider-vue />
    <service-vue />
    <our-team-vue />
    <our-services-vue />
  </div>
</template>

<script>
import SliderVue from "../components/Slider.vue";
import ServiceVue from "../components/Service.vue";
import OurTeamVue from '../components/OurTeam.vue';
import OurServicesVue from '../components/OurServices.vue';

export default {
  components: {
    SliderVue,
    ServiceVue,
    OurServicesVue,
    OurTeamVue
  }
};
</script>
