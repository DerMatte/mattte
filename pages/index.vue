<template>
  <div class="container">

    <Hero />
    <!-- <Projects /> -->
    <!-- <Contruction /> -->

    <!-- Webrpoj Start - Content Source: Lanas.dev -->
    <div class="webproj">
      <!-- Lanas.dev -->
      <div class="trianglebox">
        <div class="triangle"></div>
        <div class="textbox"><h3>Lorem, ipsum.</h3><p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Molestiae, necessitatibus.</p></div>
      </div>
      <div class="trianglebox">
        <div class="triangle"></div>
        <div class="textbox"><h3>Lorem, ipsum.</h3><p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Molestiae, necessitatibus.</p></div>
      </div>
      <div class="trianglebox">
        <div class="triangle"></div>
        <div class="textbox"><h3>Lorem, ipsum.</h3><p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Molestiae, necessitatibus.</p></div>
      </div>

    </div>
      <div class="seperator" id="webprojects">
        <hr> <p><</p>
        <nuxt-link to="#"> more |web| projects</nuxt-link>
      </div>
    <!-- Tech Blog Start - Content Source: twnt.xyz -->
    <div class="techblog">
      <div class="element">
        <nuxt-link to="#">
          <div class="circle"></div>
          <div class="circletextbox"><h3>Lorem, ipsum.</h3><p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Voluptates, cumque.</p></div>
        </nuxt-link>
      </div>
      <div class="element">
        <nuxt-link to="#">
          <div class="circle"></div>
          <div class="circletextbox"><h3>Lorem, ipsum.</h3><p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Voluptates, cumque.</p></div>
        </nuxt-link>
      </div>
      <div class="element">
        <nuxt-link to="#">
          <div class="circle"></div>
          <div class="circletextbox"><h3>Lorem, ipsum.</h3><p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Voluptates, cumque.</p></div>
        </nuxt-link>
      </div>
    </div>
    <div class="seperator" id="techblog">
        <hr> <p><</p>
        <nuxt-link to="#"> more |Tech| projects</nuxt-link>
      </div>

  </div>
</template>

<script>
import Hero from '~/components/Hero.vue'
// import Construction from '~/components/Contruction.vue'

export default {
  layout: 'default',
  generate: {
    fallback: true
  },
  components: {
    Hero,
    // Projects
    // Construction
  },
  // data() {
  //   id: this.$route.params.id,

  //   return posts [
  //     {
  //       id: '1',
  //       title: 'Test Title',
  //       content: 'lorem lorem lorem ipsum ipsum'
  //     },
  //     {
  //       id: '2',
  //       title: 'Test Title',
  //       content: 'lorem lorem lorem ipsum ipsum'
  //     },
  //     {
  //       id: '3',
  //       title: 'Test Title',
  //       content: 'lorem lorem lorem ipsum ipsum'
  //     }
  //   ]
  // }
}
</script>

<style scoped>
.container {
  margin: 0 auto;
  min-height: 100vh;
  overflow-x: hidden;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
.webproj {
  min-height: 50vh;
  width: 100vw;
  margin-top: -12em;
  display: flex;
  justify-content: space-around;
  flex-flow: row wrap;

}
/* .trianglebox {

} */
.triangle {
    /* background-image: url('https://images.unsplash.com/photo-1572177812156-58036aae439c?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1350&q=80'); */
  /* -webkit-clip-path: polygon(50% 0%, 0% 100%, 100% 100%);
  clip-path: polygon(50% 0%, 0% 100%, 100% 100%); */

  width: 0;
  height: 0;
  border-bottom: 30em solid #7361E3;
  /* border-image: url('https://images.unsplash.com/photo-1572177812156-58036aae439c?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1350&q=80'); */
  border-left: 15em solid transparent;
  border-right: 15em solid transparent;
}

.textbox {
  background-color: rgb(200,200,200);
  width: 30em;
  margin-top: 5rem;
  min-height: 10rem;
}
.textbox h3, .textbox p {
  /* margin: rem; */
  padding: 1em 2em ;
}

.seperator {
  margin-top: 2rem;
  display: flex;

  /* padding: 2rem 4rem; */
}
.seperator hr {
  width: 60vw;
  margin-left: 7em;
}
.seperator a {
  /* font-size: 1.2rem; */
  letter-spacing: 0.2em;
  word-spacing: 1.5em;
  margin-left: 2em;
}
.seperator p {
  margin-right: 1vw;
}

/* Blog article start */
.techblog {
  margin-top: 5em;
  display: flex;
  justify-content: space-around;
  flex-flow: row wrap;
  color: black;
  text-decoration: none;
  text-decoration-color: #111;

}

.techblog .circle {
  border-radius: 50%;
	width: 10vw;
	height: 10vw;
  min-width: 15em;
  min-height: 15em;
  background-color: #E37361;
  background-image: url('https://images.unsplash.com/photo-1466074395296-41cba23ce4f8?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1000&q=80');
  border-color: #E37361;
  border: 1px solid #E37361;
  /* margin: 2em 5em; */
  padding-bottom: 5em;
}
.techblog .circletextbox {
  /* padding: 2em 0; */
  background-color: #45F990;
  width: 10vw;
  min-width: 15em;
  margin-top: 5rem;
  min-height: 10rem;

}

.techblog h3, .techblog p {
  margin: 1rem;
  padding: 1rem;
}




</style>
