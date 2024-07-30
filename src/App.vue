<script setup>
import HelloWorld from './components/HelloWorld.vue'
//import TheWelcome from './components/TheWelcome.vue'; (wird für andere Seiten genutzt)
import Navbar from './components/Navbar.vue';


</script>

<template>
  
<Navbar />
 
<Homepage/>

 


<div class="shit">

<table class="shittable">
  <tr>
    <!--Space-->
    <br>
    <br>
    <!--Space-->
  </tr>  
  <tr>  
  <td class="bausteinr">
Text um irgendwie ein index zu haben was nicht so kacke aussieht (keine Ahnung wird eh von Chat GPT erledigt)
Fick diesen kasten, der soll sich mal wo anders bewegt. 

  </td>
  <td class="bausteinl">
    Text um irgendwie ein index zu haben was nicht so kacke aussieht (keine Ahnung wird eh von Chat GPT erledigt)
Fick diesen kasten, der soll sich mal wo anders bewegt. 
  </td>
</tr>

</table>
  

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

.yamoto  {
  justify-content:center!important;
  
}
</style>
