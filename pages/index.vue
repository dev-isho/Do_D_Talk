<template>
  <div>
    <slider-vue />
    <service-vue />
    <our-team-vue />
  </div>
</template>

<script>
import SliderVue from "../components/Slider.vue";
import ServiceVue from "../components/Service.vue";
import OurTeamVue from '../components/OurTeam.vue';

export default {
  components: {
    SliderVue,
    ServiceVue,
    OurTeamVue
  }
};
</script>
