<template>
    <div class="webproj">
      <!-- Lanas.dev -->
      <span class="trianglebox">
        <span class="triangle">LanasPic</span>
        <div class="textbox"><p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Molestiae, necessitatibus.</p></div>
      </div>
      <div class="trianglebox">
        <span class="triangle">LanasPic</span>
        <div class="textbox"><p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Molestiae, necessitatibus.</p></div>
      </div>
      <div class="trianglebox">
        <span class="triangle">LanasPic</span>
        <div class="textbox"><p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Molestiae, necessitatibus.</p></div>
      </div>
    </div>
</template>

<script>
export default {

}
</script>

<style>
.triangle {
  background-image: url('https://images.unsplash.com/photo-1572177812156-58036aae439c?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1350&q=80');
  -webkit-clip-path: polygon(50% 0%, 0% 100%, 100% 100%);
  clip-path: polygon(50% 0%, 0% 100%, 100% 100%);
}
</style>