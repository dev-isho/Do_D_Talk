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
import OurTeamVue from "../components/OurTeam.vue";
import OurServicesVue from "../components/OurServices.vue";

export default {
  data() {
    return {
      title: "Do D Talk"
    };
  },
  components: {
    SliderVue,
    ServiceVue,
    OurServicesVue,
    OurTeamVue
  },
  head() {
    return {
      title: this.title,
      meta: [
        {
          hid: "description",
          name: "description",
          content: "My custom description"
        }
      ]
    };
  }
};
</script>
