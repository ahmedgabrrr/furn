<template>
  <div>
    <b-carousel
      id="carousel-1"
      :interval="4000"
      controls
      indicators
      background="#ababab"
      img-width="1024"
      img-height="480"
      style="text-shadow: 1px 1px 2px #333"
    >
      <!-- Text slides with image -->
      <b-carousel-slide
        img-src="https://vue-ecom.vercel.app/img/jum1.jpg"
      ></b-carousel-slide>

      <!-- Slides with custom text -->
      <b-carousel-slide img-src="https://vue-ecom.vercel.app/img/jum2.jpg">
      </b-carousel-slide>

      <!-- Slides with image only -->
      <b-carousel-slide
        img-src="https://vue-ecom.vercel.app/img/jum3.jpg"
      ></b-carousel-slide>

      <!-- Slides with img slot -->
      <!-- Note the classes .d-block and .img-fluid to prevent browser default image alignment -->

      <!-- Slide with blank fluid image to maintain slide aspect ratio -->
      <b-carousel-slide caption="Blank Image" img-blank img-alt="Blank image">
      </b-carousel-slide>
    </b-carousel>

    <!-- <p class="mt-4">
      Slide #: {{ slide }}<br />
      Sliding: {{ sliding }}
    </p> -->
  </div>
</template>

<script>
// export default {
//   data() {
//     return {
//       slide: 0,
//       sliding: null,
//     };
//   },
//   methods: {
//     onSlideStart(slide) {
//       this.sliding = true;
//     },
//     onSlideEnd(slide) {
//       this.sliding = false;
//     },
//   },
// };
</script>
<style scoped>
</style>