<template>
  <div>
    <b-carousel
      id="carousel-1"
      v-model="slide"
      :interval="4000"
      controls
      indicators
      background="#ababab"
      img-width="1024"
      img-height="480"
      style="text-shadow: 1px 1px 2px #333;"
      @sliding-start="onSlideStart"
      @sliding-end="onSlideEnd"
    >
      <!-- Text slides with image -->
      <b-carousel-slide
        
        img-src="//st1.myideasoft.com/idea/bs/42/myassets/slider_pictures/pictures_3_7.jpg?revision=1605008358"
      ></b-carousel-slide>
      <b-carousel-slide
        
        img-src="//st1.myideasoft.com/idea/bs/42/myassets/slider_pictures/pictures_3_4.jpg?revision=1605008358"
      ></b-carousel-slide>

      <!-- Slides with custom text -->
      <b-carousel-slide img-src="//st1.myideasoft.com/idea/bs/42/myassets/slider_pictures/pictures_3_2.png?revision=1605008358">
        
      </b-carousel-slide>

      <!-- Slides with image only -->
      <b-carousel-slide img-src="//st1.myideasoft.com/idea/bs/42/myassets/slider_pictures/pictures_3_7.jpg?revision=1605008358"></b-carousel-slide>

      <!-- Slides with img slot -->
      <!-- Note the classes .d-block and .img-fluid to prevent browser default image alignment -->
      <b-carousel-slide>
        <template #img>
          <img
            
            src="//st2.myideasoft.com/idea/bs/42/myassets/slider_pictures/pictures_3_5.jpg?revision=1605008358"
            
          >
        </template>
      </b-carousel-slide>

      
      
    </b-carousel>

    
  </div>
</template>

<script>
export default {
    data() {
      return {
        slide: 0,
        sliding: null
      }
    },
    methods: {
      onSlideStart(slide) {
        this.sliding = true
      },
      onSlideEnd(slide) {
        this.sliding = false
      }
    }
}
</script>

<style>

</style>