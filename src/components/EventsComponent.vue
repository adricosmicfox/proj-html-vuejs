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
            <h1>{{eventsArray.day}}</h1>
            <h5>NOV</h5>
            <button> Get ticket</button>
          </div>
        </div>
      </div>
        
    
    </section>
</template>


<!-- *****JAVSCRIPT***** -->
<script>
export default {
name: 'EventsComponent',
  data(){
    return{
      eventsArray: [
        {
        location: 'Texas, US',
        course: 'Storytelling Workshop',
        day: '22',
        month:'NOV'
        },

        {
        location: 'New York, US',
        course: 'Painting Art Contest 2020',
        day: '10',
        month:'OCT'
        },

        {
        location: 'Hamburg, Germany',
        course: 'International Art Fair 2020',
        day: '23',
        month:'NOV'
        },

        {
        location: 'Illinois, US',
        course: 'Street Performance: Call for Artist',
        day: '15',
        month:'DEC'
        },

        {
        location: 'Illinois, US',
        course: 'Consumer Food Safety Education Conference',
        day: '22',
        month:'JUL'
        },

        {
        location: 'Dubai',
        course: 'How meditation improve your mental health?',
        day: '12',
        month:'AUG'
        },
      ]
    }
  }
}
</script>



<!-- *****CSS STYLE***** -->
<style lang="scss" scoped>
@import "../style/common.scss";

section{
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

h6{
  margin: 0;
  margin-bottom: 1rem;
}

img{
  margin-right: .3rem;
}

</style>