<script lang="ts">
  import svelteLogo from './assets/svelte.svg'
  import viteLogo from '/vite.svg'
  import Counter from './lib/Counter.svelte'
  import Navbar from './lib/Navbar.svelte'
  import About from './lib/About.svelte'
</script>

<style>
  #myVideo {
    position: fixed;
    right: 0;
    bottom: 0;
    min-width: 100%;
    min-height: 100%;
  }
</style>


<Navbar></Navbar>
<video autoplay muted loop id="myVideo">
  <source src="lib/video.mp4" type="video/mp4">
</video>
<div class="d-flex flex-column justify-content-center border border-black border-3 bg-light p-3">
  <h2>Welcome.</h2>
  <div class="d-flex flex-column">
    <a>About</a>
    <a>Music</a>
    <a>Video</a>
  </div>
</div>

<About></About>
