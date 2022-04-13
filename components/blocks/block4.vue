<template lang="pug">
.container
  h1#clientxx
  .row(data-aos="zoom-in-up")
    .col
        #block4box
        b-carousel#carousel-fade(style='text-shadow: 0px 0px 2px #000' img-width='1024' img-height='480' controls=true)
            b-carousel-slide(caption='McDonalds' img-src='https://cdn.wallpapersafari.com/81/9/ZzUw9E.jpeg')
            b-carousel-slide(caption='Jollibee' img-src='https://cdn.shopify.com/s/files/1/0580/3245/5858/files/JB-US-ZOOM-BACKGROUNDS_SEASONS_FALL_FA.jpg?v=1628113497')
            b-carousel-slide(caption='Burger King' img-src='https://wallpaperaccess.com/full/1727347.jpg')
</template>
<script>

export default {
    name:'clientxx',
    head() {
       return {
            title:"images",
            meta:[{
                hid:"",
                name:"images",
                content:"planet"
            }
            ]
       }
    },
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
<style scoped>
/* #block4box{
    background-color: antiquewhite;
} */
#block4box{
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    font-size: 5em;
}
</style>