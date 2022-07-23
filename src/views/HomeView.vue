<template>
<div class="w-full h-screen">
  <VueSlickCarousel :arrows="false" :dots="true">
      <div>
        <img class="h-screen w-full" src="https://initiate.alphacoders.com/images/695/cropped-1366-768-695548.jpg?5098">
      </div>
      <div>
        <img class="h-screen w-full" src="https://images4.alphacoders.com/688/thumb-1920-688660.jpg">
      </div>
      <div>
        <img class="h-screen w-full" src="https://images7.alphacoders.com/695/thumb-1920-695927.jpg">
      </div>
      <div>
        <img class="h-screen w-full" src="https://images5.alphacoders.com/599/thumb-1920-599012.jpg">
      </div>
    </VueSlickCarousel>
</div>
</template>

<script>
// @ is an alias to /src
 import VueSlickCarousel from 'vue-slick-carousel'
  import 'vue-slick-carousel/dist/vue-slick-carousel.css'
  import 'vue-slick-carousel/dist/vue-slick-carousel-theme.css'
export default {
  name: 'HomeView',
  components: {
    VueSlickCarousel 
  }
}
</script>
