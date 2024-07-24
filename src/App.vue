<script setup>
import HelloWorld from './components/HelloWorld.vue'
//import TheWelcome from './components/TheWelcome.vue'; (wird für andere Seiten genutzt)
import Navbar from './components/Navbar.vue';


</script>

<template>
  

  <div>
      <Navbar />
  </div>
    <img alt="CC" class="logo" src="./assets/cc_logo_2.png" width="325" height="175" />

<div class="wrapper">
  <HelloWorld msg="Wilkommen bei ComputaCenter" />
 
</div>
 
</template>

<style scoped>

.logo {
  display: block;
  margin: 0 auto 2rem;
  padding-left: 10%;
  margin: 0 2rem 0 0;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 4);
    flex-wrap: wrap;

  }



  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
    
  }
}

</style>
