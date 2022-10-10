<template>
  <section> 

    <div class="d-flex justify-content-between">
      <div class="d-flex flex-column">
        <h5>Address</h5>
        <p>382 NE 191st St #87394 Miami, FL 33179-3899</p>
        <p>+1(305) 547-9909 (9am - 5pm EST, Monday - Friday)</p>
        <p>support@maxcoach.com</p>
        <div>
          <img class="me-4 am-social-icon" src="../assets/twitter.svg" alt="">
          <img class="me-4 am-social-icon" src="../assets/facebook.svg" alt="">
          <img class="me-4 am-social-icon" src="../assets/instagram.svg" alt="">
          <img class="me-4 am-social-icon" src="../assets/linkedin.svg" alt="">
        </div>

      </div>


      <div class="am-informations d-flex justify-content-between">
        <div class="d-flex flex-column">
          <h5>Explore</h5>
          <p>Start here</p>
          <p>Blog</p>
          <p>About us</p>
        </div>

        <div class="d-flex flex-column">
          <h5>&nbsp;</h5>
          <p>Success story</p>
          <p>Courses</p>
          <p>Contact us</p>
        </div>

        <div class="d-flex flex-column">
          <h5>Informations</h5>
          <p>Membership</p>
          <p>Purchase guida</p>
          <p>Privacy policy</p>
          <p>Terms of services</p>
        </div>
      </div>
    </div>
  </section>
 </template>


<!-- *****JAVSCRIPT***** -->
<script>
export default {
name: 'FooterComponent'
}
</script>



<!-- *****CSS STYLE***** -->
<style lang="scss" scoped>
section{
    padding-left: 17rem;
    padding-right: 17rem;
}
.am-informations{
  width: 30rem;
}

.am-social-icon{
  width: 1.4rem;
  filter: invert(86%) sepia(93%) saturate(0%) hue-rotate(123deg) brightness(75%) contrast(95%);
}

</style>