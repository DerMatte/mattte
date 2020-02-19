<template>
  <nav>
    <div class="element" id="one"><nuxt-link to="#"></nuxt-link></div>
    <div class="element" id="two"><nuxt-link to="#"></nuxt-link></div>
    <div class="element" id="three"><nuxt-link to="#"></nuxt-link></div>
  </nav>
</template>

<script>
export default {

}
</script>

<style scoped>

nav {
  position: fixed;
  left: 0;
  top: 5em;
}
.element {
  width: 10em;
  height: 10em;
}
#one {
  background-color: #7361E3;
  content: '\n';
}
#two {
  background-color: #E37361;
  content: '\n';
}
#three {
  background-color: #61E373;
  content: '\n';
}




</style>
