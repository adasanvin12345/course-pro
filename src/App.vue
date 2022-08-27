<template>
  <div class="app_container">
    <div><Header></Header></div>
    <Stats></Stats>
    <Courses></Courses>
    <TopEarners></TopEarners>
    <Refer></Refer>
    <Testimonials></Testimonials>
    <Contact></Contact>
    <Footer></Footer>
  </div>
    
</template>

<script>

import Header from './components/Header'
import Stats from './components/Stats.vue';
import TopEarners from './components/Top_earners.vue';
import Refer from './components/Refer.vue';
import Testimonials from './components/Testimonials.vue';
import Contact from './components/Contact.vue';
import Courses from './components/Courses.vue';
import Footer from './components/Footer.vue';

export default {
  name: 'App',
  components: {
    Header,
    Stats,
    Courses,
    TopEarners,
    Stats,
    Refer,
    Testimonials,
    Contact,
    Courses,
    Footer
},
  // data(){
  //   return {
  //     courses:[]
  //   }
  // },
  // created(){
  //   // this.courses = [
  //   //   {
  //   //     id:1,
  //   //     bg-image: 'transparent url('./assets/wes-hicks-4-EeTnaC1S4-unsplash.png') 0% 0% no-repeat padding-box;'
  //   //   }
  //   // ]
  // }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 0px;
}
</style>
