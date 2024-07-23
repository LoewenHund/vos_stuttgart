<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue';
import Navbar from './components/Navbar.vue';


</script>

<template>
  
  <header >

     <div>
         <main><Navbar /></main>
     </div>
    
    <img alt="CC" class="logo" src="./assets/cc_logo_2.png" width="325" height="175" />

    <div class="wrapper">
      <HelloWorld msg="Wilkommen bei ComputaCenter" />
     
    </div>
  </header>

  <main>
    
    <TheWelcome />
  </main>
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
  padding-left: 10%;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
   
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}

</style>
