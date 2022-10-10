<template>
  <section>
  <div class="d-flex justify-content-around align-items-center">
    <div class="am-list-box">
      <h6 class="mb-4">WHY HESITATE TO REGISTER</h6>
      <h1 class="mb-4">Learn At Your Own Pace</h1>
      <ul class="mb-4">
        <li class="mb-3">Select & customize courses to your preferences</li>
        <li class="mb-3">Change the tutor and make arrangements</li>
        <li class="mb-3">Participate in events to join others</li>
        <li class="mb-3">Get the desired certificate delivered at house</li>
      </ul>
      <button> Download free E-Book</button>
    </div>

    <div>
      <img src="../assets/home-5-image-01.png" alt="">
    </div>
  </div>

  <div class="d-flex justify-content-around align-items-center">
    
    <div>
      <img src="../assets/home-5-image-02.png" alt="">
    </div>

    <div class="am-list-box">
      <h6  class="mb-4">WHAT ARE YOU LOOKING FOR?</h6>
      <h1  class="mb-4">Learn on your mobile anytime!</h1>
      <p  class="mb-4">Save lessons for later and revise or write notes at any time and on multiple devices on your way. Nver interfere with activities of enjoyment or other precious moments.</p>
      <button> Download free E-Book</button>
    </div>

  </div>

  </section>
</template>


<!-- *****JAVSCRIPT***** -->
<script>
export default {
name: 'LearningComponent'
}
</script>



<!-- *****CSS STYLE***** -->
<style lang="scss" scoped>
section{
    padding-left: 17rem;
    padding-right: 17rem;
    padding-bottom: 5rem;
  }

ul{
  list-style:url(../assets/check.svg) ;
}

.am-list-box{
  width: 30rem;
}

button{
  color: white;
  border: none;
  border-radius: 7px;
  padding: .3rem;
  width: 10rem;
  font-weight: 600;
}
</style>