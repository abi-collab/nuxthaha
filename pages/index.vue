<template lang="pug">
<div>
  appheader
  block1.blocks#blockOne
  #boxTwo
    block2.blocks#blockTwo
  #blockThree
    block3.blocks
  block4.blocks#blockFour
  block5.blocks
  appfooter
</div>
</template>

<script>
import appheader from '../components/appheader.vue'
import block1 from '../components/blocks/block1.vue'
import block2 from '../components/blocks/block2.vue'
import block3 from '../components/blocks/block3.vue'
import block4 from '../components/blocks/block4.vue'
import block5 from '../components/blocks/block5.vue'
import appfooter from '../components/appfooter.vue'

export default {
  name: 'IndexPage',
  components:{
    appheader,
    block1,
    block2,
    block3,
    block4,
    block5,
    appfooter

  }
}
</script>
,<style scoped>
.blocks{
  height: 100vh;
}
#blockTwo{
  background-color: white;
}
 #boxTwo{
   background-color: #75B7FD;
 }
 /* @media (max-width: 1200px) {
        br{
          display: none;
        }

      } */
</style>
