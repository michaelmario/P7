<template>
<footer class="site-footer">
<div class="w3-container w3-center">
        <div class="w3-padding-top">
            <ul class="copyList"  data-aos="fade-left" data-aos-duration="3000" data-aos-easing="ease-out-cubic">
                <li>Copyright © by
                    <a href="#" target="_blank" rel="noopener">Achille Mario | 2021</a></li>
                <li>
                    <a href="https://jigsaw.w3.org/css-validator/check/referer" target="_blank" rel="noopener">
                        <img style="border:0;width:88px;height:27px" src="https://firebasestorage.googleapis.com/v0/b/mauricodeacademy.appspot.com/o/images%2Fw3-cssRight.webp?alt=media&token=04c985a6-233c-4322-ad43-e5d973a57b85" alt="CSS Valide !" />
                    </a>

                </li>
                <li>
                    <a href="https://icons8.com/icon/111608/edit-property" target="_blank" rel="noopener">Edit Property icon by Icons8</a>
                </li>
                
            </ul>
        </div>

    </div>

</footer>
</template>

<script>
// import SocialSharing from 'vue-social-sharing';
export default {
    name: "Footer",
    components: {
      //   SocialSharing
    }
};
</script>

<style scoped>
.site-footer {
   background-color:#071c72;
    color: #fff;
}


.devise {
    padding-left: 15px;
}

.space {
    height: 150px;
}

.footerNav ul li {
    list-style: none;
}

.footerNav>ul>li>a:hover {
    color: orange;
}

.copyList>li {
    list-style: none;
    margin-top: 10px;
}

.copyList>li a {
    text-decoration: none;
    color: rgb(255, 0, 76);
}

/* ul.social-links{
  display:flex;
  flex-direction :row;
width:100% !important;
height:50px;
} */
.resp-sharing-button__link,
.resp-sharing-button__icon {
  display: inline-block
}

.resp-sharing-button__link {
  text-decoration: none;
  color: #fff;
  margin: 0.5em
}

.resp-sharing-button {
  border-radius: 5px;
  transition: 25ms ease-out;
  padding: 0.5em 0.75em;
  font-family: Helvetica Neue,Helvetica,Arial,sans-serif
}

.resp-sharing-button__icon svg {
  width: 1em;
  height: 1em;
  margin-right: 0.4em;
  vertical-align: top
}

.resp-sharing-button--small svg {
  margin: 0;
  vertical-align: middle
}

/* Non solid icons get a stroke */
.resp-sharing-button__icon {
  stroke: #fff;
  fill: none
}

/* Solid icons get a fill */
.resp-sharing-button__icon--solid,
.resp-sharing-button__icon--solidcircle {
  fill: #fff;
  stroke: none
}

.resp-sharing-button--twitter {
  background-color: #55acee
}

.resp-sharing-button--twitter:hover {
  background-color: #2795e9
}

.resp-sharing-button--pinterest {
  background-color: #bd081c
}

.resp-sharing-button--pinterest:hover {
  background-color: #8c0615
}

.resp-sharing-button--facebook {
  background-color: #3b5998
}

.resp-sharing-button--facebook:hover {
  background-color: #2d4373
}

.resp-sharing-button--tumblr {
  background-color: #35465C
}

.resp-sharing-button--tumblr:hover {
  background-color: #222d3c
}

.resp-sharing-button--reddit {
  background-color: #5f99cf
}

.resp-sharing-button--reddit:hover {
  background-color: #3a80c1
}

.resp-sharing-button--google {
  background-color: #dd4b39
}

.resp-sharing-button--google:hover {
  background-color: #c23321
}

.resp-sharing-button--linkedin {
  background-color: #0077b5
}

.resp-sharing-button--linkedin:hover {
  background-color: #046293
}

.resp-sharing-button--email {
  background-color: #777
}

.resp-sharing-button--email:hover {
  background-color: #5e5e5e
}

.resp-sharing-button--xing {
  background-color: #1a7576
}

.resp-sharing-button--xing:hover {
  background-color: #114c4c
}

.resp-sharing-button--whatsapp {
  background-color: #25D366
}

.resp-sharing-button--whatsapp:hover {
  background-color: #1da851
}

.resp-sharing-button--hackernews {
background-color: #FF6600
}
.resp-sharing-button--hackernews:hover, .resp-sharing-button--hackernews:focus {   background-color: #FB6200 }

.resp-sharing-button--vk {
  background-color: #507299
}

.resp-sharing-button--vk:hover {
  background-color: #43648c
}

.resp-sharing-button--facebook {
  background-color: #3b5998;
  border-color: #3b5998;
}

.resp-sharing-button--facebook:hover,
.resp-sharing-button--facebook:active {
  background-color: #2d4373;
  border-color: #2d4373;
}

.resp-sharing-button--twitter {
  background-color: #55acee;
  border-color: #55acee;
}

.resp-sharing-button--twitter:hover,
.resp-sharing-button--twitter:active {
  background-color: #2795e9;
  border-color: #2795e9;
}

.resp-sharing-button--tumblr {
  background-color: #35465C;
  border-color: #35465C;
}

.resp-sharing-button--tumblr:hover,
.resp-sharing-button--tumblr:active {
  background-color: #222d3c;
  border-color: #222d3c;
}

.resp-sharing-button--email {
  background-color: #777777;
  border-color: #777777;
}

.resp-sharing-button--email:hover,
.resp-sharing-button--email:active {
  background-color: #5e5e5e;
  border-color: #5e5e5e;
}

.resp-sharing-button--pinterest {
  background-color: #bd081c;
  border-color: #bd081c;
}

.resp-sharing-button--pinterest:hover,
.resp-sharing-button--pinterest:active {
  background-color: #8c0615;
  border-color: #8c0615;
}

@media(max-width:768px) {
    h2 {
        font-size: 20px;
    }
}
</style>