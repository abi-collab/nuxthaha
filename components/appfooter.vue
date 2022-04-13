<template lang="pug">
footer.site-footer
  .container
    .row
      .col-sm-12.col-md-6
        h6 It&apos;s about jun-jun devs.
        p.text-justify Deleniti atque corrupti quos dolores et quas molestias excepturi sint occaecati 
         | cupiditate non provident, similique sunt in culpa qui officia deserunt mollitia animi, 
         | id est laborum et dolorum fuga. Et harum quidem rerum facilis est et expedita distinctio. .
      .col-xs-6.col-md-3
        h6 Connect
        ul.footer-links
          li
            a Twitter
          li
            a Facebook
          li
            a Github
      .col-xs-6.col-md-3
        h6 Learn
        ul.footer-links
          li
            a qwerty.com
          li
            a crtlaltdelete.ph
          li
            a alttab.xyz
    hr
  .container
    .row
      .col-md-8.col-sm-6.col-xs-12
        p.copyright-text
          | For Educational &copy; Purpose, Nuxt Js Practice 2022 by 
          a Abi
          | .
      .col-md-4.col-sm-6.col-xs-12
        ul.social-icons
          li
            a.twitter
              b-icon(icon="twitter")

</template>
<script>
export default {
    name:'appfooter',
    head() {
       return {
            title:"something",
            meta:[{
                hid:"",
                name:"jabdsca",
                content:"sdbfvbsdnvmsmv,,slmbvsjbvjsduvbsi"
            }
            ]
       }
    }

}
</script>
<style scoped>
ul li a:hover{
    cursor: pointer;
}
.site-footer
{
  background-color:#555555;
  padding:25px 0 20px;
  font-size:15px;
  line-height:24px;
  color:#bbb;
}
.site-footer hr
{
  border-top-color:#bbb;
  opacity:0.5
}
.site-footer hr.small
{
  margin:20px 0
}
.site-footer h6
{
  color:#FF8A00;
  font-size:16px;
  text-transform:uppercase;
  margin-top:5px;
  letter-spacing:2px
}
.site-footer a
{
  color:whitesmoke;
}
.site-footer a:hover
{
  color:#BBD500;
  text-decoration:none;
}
.footer-links
{
  padding-left:0;
  list-style:none
}
.footer-links li
{
  display:block
}
.footer-links a
{
  color:whitesmoke
}
.footer-links a:active,.footer-links a:focus,.footer-links a:hover
{
  color:#BBD500;
  text-decoration:none;
}
.footer-links.inline li
{
  display:inline-block
}
.site-footer .social-icons
{
  text-align:right
}
.site-footer .social-icons a
{
  width:40px;
  height:40px;
  line-height:40px;
  margin-left:6px;
  margin-right:0;
  border-radius:100%;
  background-color:#33353d
}
.copyright-text
{
  margin:0
}
@media (max-width:991px)
{
  .site-footer [class^=col-]
  {
    margin-bottom:30px
  }
}
@media (max-width:767px)
{
  .site-footer
  {
    padding-bottom:0
  }
  .site-footer .copyright-text,.site-footer .social-icons
  {
    text-align:center
  }
}
.social-icons
{
  padding-left:0;
  margin-bottom:0;
  list-style:none
}
.social-icons li
{
  display:inline-block;
  margin-bottom:4px
}
.social-icons li.title
{
  margin-right:15px;
  text-transform:uppercase;
  color:#96a2b2;
  font-weight:700;
  font-size:13px
}
.social-icons a{
  background-color:#eceeef;
  color:#818a91;
  font-size:16px;
  display:inline-block;
  line-height:44px;
  width:44px;
  height:44px;
  text-align:center;
  margin-right:8px;
  border-radius:100%;
  -webkit-transition:all .2s linear;
  -o-transition:all .2s linear;
  transition:all .2s linear
}
.social-icons a:active,.social-icons a:focus,.social-icons a:hover
{
  color:#fff;
  background-color:#29aafe
}
.social-icons.size-sm a
{
  line-height:34px;
  height:34px;
  width:34px;
  font-size:14px
}
.social-icons a.facebook:hover
{
  background-color:#3b5998
}
.social-icons a.twitter:hover
{
  background-color:#00aced
}
.social-icons a.linkedin:hover
{
  background-color:#007bb6
}
.social-icons a.dribbble:hover
{
  background-color:#ea4c89
}
@media (max-width:767px)
{
  .social-icons li.title
  {
    display:block;
    margin-right:0;
    font-weight:600
  }
}
</style>