<template>
  <section> 
     
    <div class="d-flex flex-column align-items-center am-title">
      <h6>PEOPLE ARE PRAISING MAXCOACH</h6>
      <h1>What make they <span class="am-highlight-text">love us?</span></h1>
    </div>

    <div class="d-flex justify-content-between">
      <div class="am-card d-flex flex-column align-items-center text-center justify-content-center p-4"> 
        <img class="am-avatar" src="../assets/testimonial-avata-02.jpg" alt="woman testimonial">
        <p>I am free to learn at my own pace, follow my schedule and choose the subject I like. Great study portal for people like me.</p>
        <h6>MINA HOLLACE</h6>
        <span class="mb-5">/Freelancer</span>
      </div>  

      <div class="am-card d-flex flex-column align-items-center text-center justify-content-center p-4"> 
        <img class="am-avatar" src="../assets/testimonial-avata-04.jpg" alt="woman testimonial">
        <p>MaxCoach is my best choice. Their tutors are smart and professional when dealing with students.</p>
        <h6>MADLEY PONDOR</h6>
        <span class="mb-5">/IT Specialist</span>
      </div>  

      <div class="am-card d-flex flex-column align-items-center text-center justify-content-center p-4"> 
        <img class="am-avatar" src="../assets/testimonial-avata-01.jpg" alt="woman testimonial">
        <p>I am happy with their arrangement of lessons and subjects. They reflect a scientific investigation.</p>
        <h6>LUVIC DUBBLE</h6>
        <span class="mb-5">/Private Tutor</span>
      </div>  
    </div>

    <div class="am-certification-box d-flex flex-column align-items-center am-title">
      <h4>Start today for getting <span class="am-highlight-text">Online Certification</span></h4>
      <h1 class="mt-1">You can be your own guiding star with our help!</h1>
      <button class="mt-4">Get started now</button>
    </div>

  </section>
 </template>


<!-- *****JAVSCRIPT***** -->
<script>
export default {
name: 'OpinionComponent'
}
</script>



<!-- *****CSS STYLE***** -->
<style lang="scss" scoped>
@import "../style/common.scss";

section{
  background-color: #F8F8F8;
}

.am-certification-box{
  margin-top: 5rem;
}
.am-title{
  margin-bottom: 8rem;
 
}

.am-card{
  width: 24rem;
  height: 24rem;
  background-color: white;
  box-shadow: rgba(61, 60, 60, 0.2) 0px 10px 50px;
  border-radius: 7px;
}

.am-avatar{
  border-radius: 50%;
  width: 11rem;
  position: relative;
  bottom: 95px;
}

p{
  position: relative;
  bottom: 2rem;
  font-size: 18px;
}

</style>