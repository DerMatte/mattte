<template>
  <div class="hero">
    <div class="rects">
      <!-- Boxes in the middle with Tagline & Hero image -->
      <div class="heromiddlesection">
        <div class="heroimg">
          <img src="https://images.unsplash.com/photo-1544005313-94ddf0286df2?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=340&q=80" alt="" srcset="">
        </div>
        <aside class="sidebox">
          <h1 class="tagline">Matthias <br> - <br> Digital Craftsmenship on the web</h1>
          <div class="hireme"><h3>Hire me!</h3></div>
        </aside>
      </div>

    </div>
  </div>
</template>
<style scoped>
.hero {
  min-width: 100vw;
  min-height: 60vh;
  /* height: 600px; */
  animation: 1s appear;
  
  /* min-height: 100vh; */
  display: flex;
  justify-content: center;
  /* align-items: center; */
  text-align: center;

}
.rects {
  /* background-color:#fff; */
  background-image: linear-gradient(#45F990 1px, transparent 1px),
  linear-gradient(90deg, #45F990 1px, transparent 1px);

  background-size: 100px 100px, 100px 100px, 20px 20px, 20px 20px;
  background-position: -2px -2px, -2px -2px, -1px -1px, -1px -1px;
  width: 100vw;
  height: 800px;
  margin: 0;
  z-index: -1;
  content: '\n\n\n ha';
}
.heromiddlesection {
  display: flex;
  align-items: center;
  justify-content: center;
  margin-top: 10vh;
}
.heroimg img {
  /* margin-top: 6em;
  margin-left: 8em; */
  width: 25rem;
  border-color: #7361e3;
  border-style: solid;
  border-width: 12px;
}
.sidebox {
  background-color: #e37361;
  display: flex;
  align-content: center;
  justify-content: center;
  position: relative;
  /* float: right; */
  width: 35vw;
  /* min-width: 35em; */
  text-align: center;
  height: 15rem;
  
}
.sidebox h1 {
  margin: auto;
  font-size: 1.8rem;  
  
}
/* .sidebox hr {
  max-width: 7em;
  text-align: center;
  margin: 0 auto;

} */

.sidebox .hireme {
  display: flex;
  background-color: #45F990;
  margin-left: auto;
  margin-top: auto;
  text-align: center;
  width: 5vw;
  height: 15rem;
}
.sidebox .hireme h3 {
  /* transform-origin: 0 0;
  transform: rotate(-90deg); */
  /* position: relative; */
  /* transform: rotate(90deg); */
  /* transform-origin: 0 100%; */
  /* margin-left: 1em; */
  margin: auto;
  transform: rotate(-180deg);
  writing-mode: tb-lr;          /*  for IE  */
  writing-mode: vertical-lr;
  font-size: 1.5rem;

}





@keyframes appear {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}
</style>
