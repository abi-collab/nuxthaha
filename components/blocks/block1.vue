<template lang="pug">
#boxx
  .container
    .row
      .col#t(cols="12" md="6" sm="12")
        h1#leap(data-aos="fade-down" data-aos-duration="1000") Leap to the Future
        br
        div#text(data-aos="fade-right" data-aos-duration="1000")
          p  Today’s technology is a booming market full of exciting and innovative products. 
            | With the new Alien technology offered by JunDevs, you will experience the out of this world blast innovations.
            | Are you excited to try something new?

          b-btn(size="lg") Click Here!
      .col#d(col="12" md="6" sm="12" data-aos="fade-left" data-aos-duration="3000")
        img#stick(src="/leapingstickman.png")
</template>
<script>
import aosMixin from '../mixins/aos.js'
export default {
    name:'block1',
    mixins: [aosMixin],
    head() {
       return {
            title:"Leap to the Future",
            meta:[{
                hid:"",
                name:"Leap to the Future",
                content:"Today’s technology is a booming market full of exciting and innovative products. With the new Alien technology offered by JunDevs, you will experience the out of this world blast innovations. Are you excited to try something new?"
            }
            ]
       }
    },
    methods:{
        prank() {
            alert('It`s a Prank! :-)');
            console.log('askjgcfakiuygcuyia');
        }
    }

}
</script>
<style scoped>
#t{
    padding-top:200px;
}
#leap{
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    font-size: 5em;
}
p{
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
}
/* #boxx{
    background-image: url('https://images.pexels.com/photos/3184160/pexels-photo-3184160.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1');
    background-repeat: no-repeat;
    background-size: 100%;
} */
p{
    letter-spacing: 1px;
    line-height: 1.5;
}
#stick{
    margin-top:300px;
    /* padding-left: 150px; */
    height: 500px;
    transform: rotate(25deg);
    opacity: .10;
  
}
col{
    border:solid green 1px;
}
 @media (max-width: 1200px) {
        #d {
          display: none;
        }
      }
</style>