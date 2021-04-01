<template>
<div id="app">
 <navbar /><br/>
 <section-1 /><br/>
 <section-2 /><br/>
 <section-3 /><br/>
 <section-4 /><br/>
 <section-5 /><br/>
 <section-6 /><br/>
 <section-7 /><br />
 </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld';
import Navbar from './components/navbar.vue';
import Section1 from './components/section1.vue';
import Section2 from './components/section2.vue';
import Section3 from './components/section3.vue';
import Section4 from './components/section4.vue';
import Section5 from './components/section5.vue';
import Section6 from './components/section6.vue';
import Section7 from './components/section7.vue';

export default {
  name: 'App',

  components: {
    
    Navbar,
    Section1,
    Section2,
    Section3,
    Section4,
    Section5,
    Section6,
    Section7,
  },

  data: () => ({
    //
  }),
};
</script>
