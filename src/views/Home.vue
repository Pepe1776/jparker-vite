<script>
import Navbar from '../components/Navbar.vue';
import Main from '../components/Main.vue';
import Features from '../components/Features.vue';
import Hero from '../components/Hero.vue';
import Form from '../components/Form.vue';
import Footerb from '../components/Footerb.vue';

export default {
components: {
  Navbar, 
  Main, 
  Features,
  Hero, 
  Form, 
  Footerb, 
}
}

</script>

<template>
<div>
    <Navbar />
    <Main />
    <Features />
    <Hero />
    <Form />
    <Footerb />
  </div>
</template>
