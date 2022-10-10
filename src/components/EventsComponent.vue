<template>
  <section>
     <div class="d-flex justify-content-around align-items-center">
        <div class="d-flex flex-column align-items-center">
          <h6>GET IN CONTACT NOW</h6>
          <h1>Upcoming Events</h1>
        </div>
      </div>

      
      <div class="d-flex justify-content-between flex-wrap">
        <!-- ***EVENT*** -->
        <div class="am-event d-flex p-4 justify-content-between">
          <div class="d-flex flex-column align-self-center"> 
            <h6><img src="../assets/geo-alt-fill.svg" alt="">Texas,US</h6>
            <h5>Storytelling Workshop</h5>
          </div>
         
          <div class="d-flex flex-column align-items-center">
            <h1>22</h1>
            <h5>NOV</h5>
            <button> Get ticket</button>
          </div>
        </div>

        <!-- ***EVENT*** -->
        <div class="am-event d-flex p-4 justify-content-between">
          <div class="d-flex flex-column align-self-center"> 
            <h6><img src="../assets/geo-alt-fill.svg" alt="">Texas,US</h6>
            <h5>Storytelling Workshop</h5>
          </div>
         
          <div class="d-flex flex-column align-items-center">
            <h1>22</h1>
            <h5>NOV</h5>
            <button> Get ticket</button>
          </div>
        </div>

            <!-- ***EVENT*** -->
            <div class="am-event d-flex p-4 justify-content-between">
          <div class="d-flex flex-column align-self-center"> 
            <h6><img src="../assets/geo-alt-fill.svg" alt="">Texas,US</h6>
            <h5>Storytelling Workshop</h5>
          </div>
         
          <div class="d-flex flex-column align-items-center">
            <h1>22</h1>
            <h5>NOV</h5>
            <button> Get ticket</button>
          </div>
        </div>

        <!-- ***EVENT*** -->
        <div class="am-event d-flex p-4 justify-content-between">
          <div class="d-flex flex-column align-self-center"> 
            <h6><img src="../assets/geo-alt-fill.svg" alt="">Texas,US</h6>
            <h5>Storytelling Workshop</h5>
          </div>
         
          <div class="d-flex flex-column align-items-center">
            <h1>22</h1>
            <h5>NOV</h5>
            <button> Get ticket</button>
          </div>
        </div>

            <!-- ***EVENT*** -->
            <div class="am-event d-flex p-4 justify-content-between">
          <div class="d-flex flex-column align-self-center"> 
            <h6><img src="../assets/geo-alt-fill.svg" alt=""> Texas,US</h6>
            <h5>Storytelling Workshop</h5>
          </div>
         
          <div class="d-flex flex-column align-items-center">
            <h1>22</h1>
            <h5>NOV</h5>
            <button> Get ticket</button>
          </div>
        </div>

        <!-- ***EVENT*** -->
        <div class="am-event d-flex p-4 justify-content-between">
          <div class="d-flex flex-column align-self-center"> 
            <h6><img src="../assets/geo-alt-fill.svg" alt="">Texas,US</h6>
            <h5>Storytelling Workshop</h5>
          </div>
         
          <div class="d-flex flex-column align-items-center">
            <h1>22</h1>
            <h5>NOV</h5>
            <button> Get ticket</button>
          </div>
        </div>
      </div>

      <div class="d-flex justify-content-center mt-5"> 
        <h6>Excited about our event? View all events <img src="../assets/arrow-right.svg" alt=""> </h6>
      </div>
        
    
    </section>
</template>


<!-- *****JAVSCRIPT***** -->
<script>
export default {
name: 'EventsComponent'
}
</script>



<!-- *****CSS STYLE***** -->
<style lang="scss" scoped>
section{
    padding-left: 17rem;
    padding-right: 17rem;
    padding-bottom: 10rem;
    background-image: url(../assets/wave3.svg);
    background-repeat: no-repeat;
    background-position-y: bottom;
}

.am-event{
  margin-top: 2rem;
  width: 37.4rem;
  background-color: #F8F8F8;
  border-radius: 4px;
}

button{
  color: white;
  border: none;
  border-radius: 7px;
  padding: .3rem;
  width: 10rem;
  font-weight: 600;
}

h6{
  margin: 0;
  margin-bottom: 1rem;
}

img{
  margin-right: .3rem;
}

</style>