<template>
  <div>
    <nuxt />
  </div>
</template>

<script>
import Naviator from '~/components/Navigator.vue'

export default {
  components: {
    Navigator,
  }
}
</script>

<style>
html {
  font-family: 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
  background-color: #fff;
  color: #111;
  /* // Dev Ed: 10 CSS Tricks */
  scroll-behavior: smooth;
  font-size: 62.5%;

}
@media screen and (max-width: 700px) {
  html {
    font-size: 55%;
  }
}
/* @media screen and (max-width: 500px) {
  html {
    font-size: 50%;
  }
} */
*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}


</style>
