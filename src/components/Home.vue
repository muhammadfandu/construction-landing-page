<template>
  <Navbar />
  <Carousel />
  <Welcome />
  <OurService />
  <Offer />
  <Projects />
  <Members />
  <Testimonial />
  <News />
  <Subscribe />
</template>

<script>
import Navbar from './layout/Navbar.vue';
import Carousel from './Carousel.vue';
import Welcome from './Welcome.vue';
import OurService from './OurService.vue';
import Offer from './Offer.vue';
import Projects from './Projects.vue';
import Members from './Members.vue';
import Testimonial from './Testimonial.vue';
import News from './News.vue';
import Subscribe from './Subscribe.vue';

export default {
  name: 'Home',
  components: {
    Navbar,
    Carousel,
    Welcome,
    OurService,
    Offer,
    Projects,
    Members,
    Testimonial,
    News,
    Subscribe,
  },
  props: {},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped></style>
