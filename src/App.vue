<script setup>
import HelloWorld from './components/HelloWorld.vue'
//import TheWelcome from './components/TheWelcome.vue'; (wird für andere Seiten genutzt)
import Navbar from './components/Navbar.vue';


</script>

<template>
  
<Navbar />
 
<Homepage/>

 




 
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

.yamoto  {
  justify-content:center!important;
  
}
</style>
