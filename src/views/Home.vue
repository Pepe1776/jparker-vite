<script>
import Navbar from '../components/Navbar.vue';
import Main from '../components/Main.vue';
import Features from '../components/Features.vue';
import Hero from '../components/Hero.vue';
// import Form from '../components/Form.vue';
import Footerb from '../components/Footerb.vue';
import About from '../components/About.vue';
import Demo from '../components/Demo.vue';

export default {
components: {
  Navbar, 
  Main, 
  Features,
  Hero, 
  // Form, 
  Footerb, 
  About,
  Demo,
}
}

</script>

<template>
<div>
    <Navbar />
    <Main />
    <Hero />
    <About />
    <Demo />
    <Features />
    <!-- <Form /> -->
    <Footerb />
  </div>
</template>
