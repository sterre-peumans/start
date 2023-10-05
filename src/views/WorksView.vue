<script setup>
import FooterComp from '../components/FooterComp.vue'


import { Carousel } from 'flowbite-vue'

const pictures = [
  {
    'src': 'src/assets/images/0.png',
    'alt': 'Picture 2',
  },
  {
    'src': 'src/assets/images/1.jpg',
    'alt': 'Picture 2',
  },
  {
    'src': 'src/assets/images/2.jpg',
    'alt': 'Picture 2',
  },
]

</script>

<template>
  <div class="works">
    <h1 class="text-3xl font-bold">
      This is a page on my Work
    </h1>
    <div>
      <h3>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce mollis mauris non orci hendrerit, vel accumsan metus scelerisque. Nullam arcu mauris, bibendum ut dui at, ultricies elementum tellus. Vivamus et commodo tortor, sed cursus mauris. Cras non ipsum vel velit commodo eleifend. Maecenas iaculis nisl nec accumsan mattis. Praesent et egestas enim, non blandit arcu. Vestibulum egestas pharetra magna quis pharetra. Duis dignissim ornare scelerisque. Vestibulum id aliquam ligula. In ullamcorper ligula ac elit interdum vestibulum. Sed et hendrerit diam.
      </h3>
    </div>
    <div class="pt-4 pb-4">
      <Carousel :pictures="pictures"></Carousel>
    </div>
    <div>
      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce mollis mauris non orci hendrerit, vel accumsan metus scelerisque. Nullam arcu mauris, bibendum ut dui at, ultricies elementum tellus. Vivamus et commodo tortor, sed cursus mauris. Cras non ipsum vel velit commodo eleifend. Maecenas iaculis nisl nec accumsan mattis. Praesent et egestas enim, non blandit arcu. Vestibulum egestas pharetra magna quis pharetra. Duis dignissim ornare scelerisque. Vestibulum id aliquam ligula. In ullamcorper ligula ac elit interdum vestibulum. Sed et hendrerit diam.
    </div>

    <FooterComp />
  </div>
</template>


<style>
</style>
