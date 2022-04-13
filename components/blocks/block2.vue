<template lang="pug">
.container
  .row
    .col
    .col-8(cols="12" md="10" sm="12")
       h1#about(data-aos="fade-right") About Us
       br
       #des(data-aos="fade-left")
          p  At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis praesentium 
           | voluptatum deleniti atque corrupti quos dolores et quas molestias excepturi sint occaecati 
           | cupiditate non provident, similique sunt in culpa qui officia deserunt mollitia animi, id 
           | est laborum et dolorum fuga. Et harum quidem rerum facilis est et expedita distinctio. Nam 
           | libero tempore, cum soluta nobis est eligendi optio cumque nihil impedit quo minus id quod.
          
          
          br
          p Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, 
           | totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae 
           | vitae dicta sunt explicabo. Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit 
           | aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt. 
           
          
    .col
</template>
<script>
import aosMixin from '../mixins/aos.js'
export default {
    name:'block1',
       mixins: [aosMixin],
    head() {
       return {
            title:"About Us",
            meta:[{
                hid:"",
                name:"about us",
                content:"Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium"
            }
            ]
       }
    }

}
</script>
<style scoped>
.col-6{
    padding-top:150px;
    text-align: center;
}
/* p{
    letter-spacing: 2px;
    line-height: 3;
} */
#about{
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    font-size: 5em;
    margin-top: 50px;
}

</style>