<script setup>

</script>





<template>
   <ul id="grid-container">
      <img src="/Logo_suit.png" href="#index" alt="CC Logo" width="80" height="50" class="imgindex">
      <li><a class="white" href="#/Dokumentation">Dokumentation</a></li>
      <li><a class="white" href="#news">Tool</a></li>
      <li><a class="white" href="#contact">Anfänger</a></li>
      <li><a class="white" href="#about">News</a></li>
      <li><a class="white" href="#about">Support</a></li>
      <button class="bkontakt"> Kontakt</button>

   
   
    </ul>
</template>

<style lang="css">

ul {
  list-style-type: none;
  margin: 0;
  padding-top: 4%;
  padding-bottom: 0.35%;
  position:fixed;
  top: 0%;
  width: 100%;
  background-color: rgb(17, 16, 16);
  text-align: left;
  /*mix-blend-mode:color-burn;*/
  z-index: 10;
}

li {
  display: inline;
  float: center;
  margin-right: 3%;
  padding-top: 8px;
  margin-left: 5%;
  padding-left: 100px;

}
.bkontakt{
  color: aliceblue;
  background-color: rgb(17, 16, 16);
  margin-right: 0px;
}



#grid-container {
  border: 1px solid rgb(5, 5, 5);
  background-color: rgb(0, 0, 0);
  grid-template-columns: 1fr 1fr 1fr;
  row-gap: 50px;
}

#grid-container > div {
  background-color: rgb(0, 0, 0);
}


</style>