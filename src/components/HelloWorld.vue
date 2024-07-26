<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div class="greetings">
    <h1 class="blue">{{ msg }}</h1>
    <h3>
      <!--Die Orientierung für neue Kollegen-->
      <!--<a href="https://vitejs.dev/" target="_blank" rel="noopener">Erfahrene Kollegen</a>+-->
      <!--<a href="https://vuejs.org/" target="_blank" rel="noopener">Spezialisierte Kollegen.</a>-->
    </h3>
  </div>


</template>




<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  position: relative;
  top: -50px;
}

h3 {
  font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
