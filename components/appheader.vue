<template lang="pug">
  .header
    .container(data-aos="zoom-in")
      a.logo(href='#default') jun-jun Devs
      .header-right
        a(href='#boxx') Home
        a(href='#about') About Us
        a(href='#mlm') Projects
        a(href='#clientxx') Clients
        a(href='#register') Register
</template>
<script>
import aosMixin from './mixins/aos.js'
export default {
    name:'appheader',
    mixins: [aosMixin],
      head() {
       return {
            title:"jun-jun Devs",
            meta:[{
                hid:"",
                name:"junjun",
                content:"Leap to the Future"
            }
            ]
       }
    },
}
</script>
<style scoped>
.header {
  overflow: hidden;
  /* background-color: #0B315E; */
  padding: 20px 10px;
  background: #BBD500;
}
.header a {
  float: left;
  color: black;
  text-align: center;
  padding: 12px;
  text-decoration: none;
  font-size: 18px;
  line-height: 25px;
  border-radius: 4px;
  font-size: 14px;
}
.header a.logo {
  font-size: 25px;
  font-weight: bold;
}
.header a:hover {
  color: black;
}
.header a.active {
  background-color: dodgerblue;
  color: white;
}
.header-right {
  float: right;
}
@media screen and (max-width: 500px) {
  .header a {
    float: none;
    display: block;
    text-align: left;
  }
  .header-right {
    float: none;
  }
}
</style>