<template lang="pug">
.container#register
  .row(data-aos="zoom-in-up")
    .col(cols="12" md="10" sm="12")
      h1 Claim Your Free POS & MLM System!
      br
      p  We would love to sent you to Planet Jupiter and claim your FREE Point of Sale and Multi-Level Marketing System.
        | Enjoy the benefits of undeniable best performance systems built with advance Alien Technology.
        | It is an exciting experience in our world today, are you motivated to grab them?
    .col-1#col1
    .col(cols="12" md="10" sm="12")
      div
        b-card#card
            h5#reg Register Now!
            hr
            br
            b-form-group.formGroup(label='Firstname:' label-for='nested-street' label-cols-sm='4' label-align-sm='right')
                b-form-input#nested-street
            b-form-group.formGroup(label='Lastname:' label-for='nested-city' label-cols-sm='4' label-align-sm='right')
                b-form-input#nested-city
            b-form-group.formGroup(label='Age:' label-for='nested-state' label-cols-sm='4' label-align-sm='right')
                b-form-input#nested-state(type="number")
            b-form-group.formGroup(label='Contact No.:' label-for='nested-country' label-cols-sm='4' label-align-sm='right')
                b-form-input#nested-country
            //- b-form-group.mb-0(label='Ship via:' label-cols-sm='3' label-align-sm='right' v-slot='{ ariaDescribedby }')
            //-     b-form-radio-group.pt-2(:options="['Air', 'Courier', 'Mail']" :aria-describedby='ariaDescribedby')
            #btnDiv
              b-btn(variant="success" size="lg") Submit 

</template>
<script>
import aosMixin from '../mixins/aos.js'
export default {
    name:'block1',
     mixins: [aosMixin],
    head() {
       return {
            title:"Claim Your Free",
            meta:[{
                hid:"",
                name:"Claim Your Free POS & MLM System!",
                content:"Claim Your Free POS & MLM System!. We would love to sent you to Planet Jupiter and claim your FREE Point of Sale and Multi-Level Marketing System."
            }
            ]
       }
    }

}
</script>
<style scoped>

#btnDiv{
    padding:30px;
    text-align: center;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    
}
#reg{
    text-align: center;
    margin: 30px;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
   
}
#card{
    box-shadow: 0px 0px 10px grey;
}
@media (max-width: 1200px) {
        h1{
            font-size: 25px;
            text-align: center;
        }
        p{
            text-align: center;
        }
        #col1{
            display:none
        }
        .row{
            margin-top:0px;
        }

      }
</style>