<template>
  <section>
    <div>
      <div class="d-flex flex-column align-items-center mb-5">
        <h6>CHOOSE WHERE YOU'D LIKE TO BEGIN</h6>
        <H1>Latest featured Courses</H1>
      </div>
      

      <div class="d-flex flex-wrap justify-content-between mb-5">

        <div class="am-card d-flex flex-column justify-content-between">
          <img class="am-photo" src="../assets/course-02-480x298.jpg" alt="">
          <div class="d-flex flex-column px-4">
            <div class="d-flex align-items-center"> 
              <img class="am-little-avatar" src="../assets/73ee246daf47502812ccefc84bf02898 (1).jpeg" alt="">
              <p class="m-0 ms-2">Blanche Fields</p>
            </div>
            <h5 class="mt-2">Learning to Write as a Professional Author</h5>
            <div class="d-flex"> 
              <p>20 Lessons</p>
              <p class="ms-3">50 Students</p>
            </div>
          </div>
        </div>

        <div class="am-card d-flex flex-column justify-content-between">
          <img class="am-photo" src="../assets/stock-full-hd-03-480x298.jpg" alt="">
          <div class="d-flex flex-column px-4">
            <div class="d-flex align-items-center"> 
              <img class="am-little-avatar" src="../assets/d0d504142acfde820eef2f11feea6253 (1).jpeg" alt="">
              <p class="m-0 ms-2">Maggie Strickland</p>
            </div>
            <h5 class="mt-2">Customer-centric Info-Tech Strategies</h5>
            <div class="d-flex"> 
              <p>24 Lessons</p>
              <p class="ms-3">769 Students</p>
            </div>
          </div>
        </div>

        <div class="am-card d-flex flex-column justify-content-between">
          <img class="am-photo" src="../assets/stock-full-hd-04-480x298.jpg" alt="">
          <div class="d-flex flex-column px-4">
            <div class="d-flex align-items-center"> 
              <img class="am-little-avatar" src="../assets/d0d504142acfde820eef2f11feea6253 (1).jpeg" alt="">
              <p class="m-0 ms-2">Maggie Strickland</p>
            </div>
            <h5 class="mt-2">Learning to Write as a Professional Author</h5>
            <div class="d-flex"> 
              <p>20 Lessons</p>
              <p class="ms-3">50 Students</p>
            </div>
          </div>
        </div>

        <div class="am-card d-flex flex-column justify-content-between">
          <img class="am-photo" src="../assets/stock-full-hd-06-480x298.jpg" alt="">
          <div class="d-flex flex-column px-4">
            <div class="d-flex align-items-center"> 
              <img class="am-little-avatar" src="../assets/73ee246daf47502812ccefc84bf02898 (1).jpeg" alt="">
              <p class="m-0 ms-2">Blanche Fields</p>
            </div>
            <h5 class="mt-2">Accademic Listening and Note-taking</h5>
            <div class="d-flex"> 
              <p>14 Lessons</p>
              <p class="ms-3">67 Students</p>
            </div>
          </div>
        </div>

        <div class="am-card d-flex flex-column justify-content-between">
          <img class="am-photo" src="../assets/course-featured-image-01-480x298.jpg" alt="">
          <div class="d-flex flex-column px-4">
            <div class="d-flex align-items-center"> 
              <img class="am-little-avatar" src="../assets/73ee246daf47502812ccefc84bf02898 (1).jpeg" alt="">
              <p class="m-0 ms-2">Blanche Fields</p>
            </div>
            <h5 class="mt-2">Master jQuery in a Short Period of Time</h5>
            <div class="d-flex"> 
              <p>6 Lessons</p>
              <p class="ms-3">51 Students</p>
            </div>
          </div>
        </div>

        <div class="am-card d-flex flex-column justify-content-between">
          <img class="am-photo" src="../assets/stock-full-hd-05-480x298.jpg" alt="">
          <div class="d-flex flex-column px-4">
            <div class="d-flex align-items-center"> 
              <img class="am-little-avatar" src="../assets/73ee246daf47502812ccefc84bf02898 (1).jpeg" alt="">
              <p class="m-0 ms-2">Blanche Fields</p>
            </div>
            <h5 class="mt-2">Introduction to Javascript for Beginners</h5>
            <div class="d-flex"> 
              <p>14 Lessons</p>
              <p class="ms-3">76 Students</p>
            </div>
          </div>
        </div>
      </div>

    <div class="d-flex justify-content-center mb-5">
      <button> View all courses</button>
    </div>
          

    </div>
    
  </section>
</template>


<!-- *****JAVSCRIPT***** -->
<script>
export default {
name: 'CoursesComponent'
}
</script>



<!-- *****CSS STYLE***** -->
<style lang="scss" scoped>
@import "../style/common.scss";

section{
   background: rgb(244,244,244);
   background: linear-gradient(0deg, rgba(244,244,244,1) 0%, rgba(255,255,255,1) 100%);
   border-bottom-right-radius: 90% (200px);
   border-bottom-left-radius: 90% (200px);
}

.am-card{
  width: 24rem;
  height: 26rem;
  padding: 1rem;
}

.am-photo{
    border-top-left-radius: 7px;
    border-top-right-radius: 7px;
  }

.am-little-avatar{
  border-radius: 50px;
  width: 3rem;
}


</style>