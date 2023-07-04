<script>
    import { Carousel } from 'flowbite-svelte'
    import { images } from './imageData/+server.js';
    let showThumbs=false
    let showCaptions=false
  </script>
  
  <div class="max-w-4xl">
    <Carousel {images} {showThumbs} {showCaptions}/>
  </div>