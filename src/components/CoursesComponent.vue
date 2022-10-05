<template>
  <section>
    <div>
      <div class="d-flex flex-column align-items-center">
        <h6>CHOOSE WHERE YOU'D LIKE TO BEGIN</h6>
        <H1>Latest featured Courses</H1>
      </div>
      

      <div>

        <div class="am-card d-flex flex-column">
          <img class="am-photo" src="../assets/course-02-480x298.jpg" alt="">
          <div class="d-flex flex-column px-4">
            <div class="d-flex"> 
              <img class="am-little-avatar" src="../assets/73ee246daf47502812ccefc84bf02898 (1).jpeg" alt="">
              <p>Blanche Fields</p>
            </div>
            <h5>Learning to Write as a Professional Author</h5>
            <div class="d-flex"> 
              <p>20 Lessons</p>
              <p>50 Students</p>
            </div>
          </div>
        </div>


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
section{
    padding-left: 17rem;
    padding-right: 17rem;
}

.am-card{
  width: 25rem;
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