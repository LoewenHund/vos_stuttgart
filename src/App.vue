<script setup>
import HelloWorld from './components/HelloWorld.vue'
//import TheWelcome from './components/TheWelcome.vue'; (wird für andere Seiten genutzt)
import Navbar from './components/Navbar.vue';
import Avatar from './components/Avatar.vue';
let titel = "Willkommen bei ComputaCenter";
titel = titel.toUpperCase();
</script>

<template>
  
<Navbar />
 
<Homepage/>

 <div class="htext">
  <h1 id="titel"> Willkommen auf der Technik Seite von ComputaCenter im DLR </h1>
 </div>
<!-- LOGO für die Homepage -->

 <div>
  <img src="/Logo_suit.png" href="#index" alt="Logo" width="400" height="250" class="hbild">
</div>

<div class="shit">

<table class="htext2">
  <td>
    Ob frisch im Team oder schon ein alter Hase in der IT - auf dieser Seite findest du alles, was du für deine tägliche Arbeit als Technik*in bei ComputaCenter brauchst. 

  </td>
</table>


<table class="shittable">
  <tr>
    <!--Space-->
    <br>
    <br>
    <!--Space-->
  </tr>  
  <tr>  
  <td class="bausteinr">
    <img src="/Logo_suit.png" href="" alt="Logo" width="250" height="250" class="imghomepage2" >
    
  </td>
  <td class="bausteinl">
Für Einsteiger bieten wir einen klaren Überblick über Tools, Prozesse und erste Schritte im technischen Umfeld ComputaCenter - damit du von Anfang an souverän durchstarten kannst. 
  </td>
</tr>

</table>
  
<table class="shittable2">
  
  <tr>
        <!--Space-->
        <br>
    <br>
    <!--Space-->
   
  </tr>  
  <tr>  

  <td class="bausteinr">
    
Für erfahrene Kolleg*innen ist diese Plattform eine zentrale Anlaufstelle, um auf dem Laufenden zu bleiben: Aktuelle IT-News, technische Updates, neue Tools und praxisnahe Tipps aus dem Field - 
alles kompakt und greifbar. 

  </td>
  <td class="bausteinl">
<img src="/Logo_suit.png" href="" alt="Logo" width="250" height="250" class="imghomepage2">
  </td>
</tr>

<tr>  
  
  <td class="bausteinr">
        <!--Space-->
        <br>
    <br>
    <!--Space-->
        <!--Space-->
        <br>
    <br>
    <!--Space-->
    <img src="/Logo_suit.png" href="" alt="Logo" width="250" height="250" class="imghomepage2" >

  </td>
  <td class="bausteinl">
    Du suchst vertiefendes Wissen? Kein Problem. Hier findest du auch: 
    - Artikel und Leitfäden zu aktuellen IT-Themen 
    - Best Practices aus dem Techniker-Alltag
  </td>
</tr>

</table>
</div>

<div>
  <h1> Unser Ziel ist es, Know-how zugänglich zu machen. Praxisnah. Verständlich. Immer aktuell.</h1> 
</div>
</template>

<style scoped>

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
