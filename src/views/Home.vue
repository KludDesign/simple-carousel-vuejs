<template>
  <div class="home">
    <carousel>
      <carousel-slide>
        <img src="https://loremflickr.com/630/300/dog" alt="">
      </carousel-slide>
      <carousel-slide>
        <img src="https://loremflickr.com/630/300/paris" alt="">
      </carousel-slide>
      <carousel-slide>
        <img src="https://loremflickr.com/630/300/cat" alt="">
      </carousel-slide>
    </carousel>
  </div>
</template>

<script>
// @ is an alias to /src
import Carousel from '@/components/Carousel.vue'
import CarouselSlide from '@/components/CarouselSlide.vue'

export default {
  name: 'home',
  components: {
    Carousel,
    CarouselSlide
  }
}
</script>
