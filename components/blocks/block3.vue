<template lang="pug">
.container-fluid#mlm
  .row
    .col(cols="12" md="10" sm="12")
      b-card.cardk(data-aos="zoom-in-down")
        h1 JunJun's MLM System
        br
        p  Nam libero tempore, cum soluta nobis est 
        |eligendi optio cumque nihil impedit quo minus id quod maxime placeat 
        |facere possimus, omnis voluptas assumenda est, omnis dolor repellendus. 
     
        br
        br
        img.imahe(src='https://www.formget.com/wp-content/uploads/2018/08/bitmlm-mlm-php-script.jpg')
      
    .col(cols="12" md="10" sm="12")
      b-card.cardk(data-aos="zoom-in-up")
        img.imahe(src='https://financesonline.com/uploads/2020/01/vend-dashboard-1-1024x576.png')
        br
        br
        br
        h1 JunJun's POS System
        br
        p  Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam 
        |rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae.
        
</template>
<script>
import aosMixin from '../mixins/aos.js'
export default {
    name:'block1',
    mixins: [aosMixin],
    head() {
       return {
            title:"junjun Projects",
            meta:[{
                hid:"",
                name:"junjun Projects",
                content:"MLM System, POS System"
            }
         ]
       }
    }

}
</script>
<style scoped>
.col{
    text-align: center;
    /* padding-left: 200px;
    padding-right: 200px; */
}
/* #col1{
    padding-top:200px;
}
#col2{
    padding-top:10%;
} */
.imahe{
    width:100%;
}
h1{
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    font-size: 3em;
}
@media (max-width: 1200px) {
.col{
    padding-left: 0px;
    padding-right: 0px;
}
#col1{
    padding-top:0px;
}
#col2{
    padding-top:0;
}
      }
.row{
    margin-top: 150px;
}
@media (max-width: 1200px) {
        h1 {
          font-size: 25px;
        }
        .cardk{
            margin: 2px;
        }

      }

</style>