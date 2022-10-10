<template>
    <section> 
    <div class="d-flex flex-column align-items-center mt-5">
      <h6>START LEARNING CODING LANGUAGES</h6>
      <H1 class="mt-3 mb-5">Build Your Dream TODAY</H1>
    </div>
    
    <div class="am-box-padding d-flex mt-5 justify-content-between"> 

      <div class="text-center am-small-box">
      <img src="../assets/home-5-image-box-01.png" alt="">
      <h4 class="mt-3">Idea Discussion</h4>
      <p>Get teamed up with the specialists who work and teach codin for years at famous universities.</p>
      <h6>Start now <img src="../assets/arrow-right.svg" alt=""></h6>
      </div>

      <div class="text-center am-small-box">
      <img src="../assets/home-5-image-box-02.png" alt="">
      <h4 class="mt-3">Web Development</h4>
      <p>Learn to start building a webpage from scratch. You decide your own pace, course and speed.</p>
      <h6>Start now <img src="../assets/arrow-right.svg" alt=""></h6>
      </div>

      <div class="text-center am-small-box">
      <img src="../assets/home-5-image-box-03.png" alt="">
      <h4 class="mt-3">System Administration</h4>
      <p>Learners are encouraged to study the mechanism and structure of system administration.</p>
      <h6>Start now <img src="../assets/arrow-right.svg" alt=""></h6>
      </div>

      <div class="text-center am-small-box">
      <img src="../assets/home-5-image-box-04.png" alt="">
      <h4 class="mt-3">Graphic Design</h4>
      <p>Have a passion for graphics and arts? Show your talents with confidenxe and self-assertiveness.</p>
      <h6>Start now <img src="../assets/arrow-right.svg" alt=""></h6>
      </div>
    </div>

    <div class="am-box-padding d-flex justify-content-around align-items-center mt-5">
      <div>
        <img src="../assets/about-us-03-image-01.png" alt="">
      </div>

      <div class="am-stunning-box">
        <h1>Construct A Stunning Career Perspective</h1>

        <div class="am-foldable-box d-flex align-items-center">
          <h5>Multiple Platforms Supported for Teaching & Studying</h5>
        </div>

        <div class="am-foldable-box d-flex align-items-center">
          <h5>Multiple Course Participation at the Same Time</h5>
        </div>

        <div class="am-foldable-box d-flex align-items-center">
          <h5>Track Study Progress & Deliver Prompt Feedback</h5>
        </div>
      </div>
    </div>

    <div class="am-numbers-box d-flex justify-content-around align-items-center">
      <div>
        <h1>1.926</h1>
        <h6>FINISHED SESSIONS</h6>
      </div>

      <div>
        <h1>3.092+</h1>
        <h6>ENROLLED LEARNERS</h6>
      </div>

      <div>
        <h1>200</h1>
        <h6>ONLINE INSTRUCTORS</h6>
      </div>

      <div>
        <h1>100%</h1>
        <h6>SATISFACTION RATE</h6>
      </div>
    </div>
  </section>
</template>


<!-- *****JAVSCRIPT***** -->
<script>
export default {
name: 'BuildDreamComponent'
}
</script>



<!-- *****CSS STYLE***** -->
<style lang="scss" scoped>
@import "../style/common.scss";

.am-small-box{
  width: 23% ;
}

.am-stunning-box{
  width: 35rem;
}
.am-foldable-box{
  margin-top: 2rem;
  width: 40rem;
  height: 4rem;
  border-radius: 4px;
  box-shadow: rgba(61, 60, 60, 0.1) 0px 10px 50px;

  h5{
    margin-left: 1rem;
    margin-bottom: 0;
  }
 }
 
 .am-numbers-box{
  background-color: #FAF8F6;
  height: 13rem;
  margin-top: 5rem;

  div{
    text-align: center;

  }
}

</style>