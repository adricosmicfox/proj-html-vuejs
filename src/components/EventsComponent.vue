<template>
  <section>
     <div class="d-flex justify-content-around align-items-center">
        <div class="d-flex flex-column align-items-center">
          <h6>GET IN CONTACT NOW</h6>
          <h1>Upcoming <span class="am-highlight-text">Events</span></h1>
        </div>
      </div>

      
      <div class="d-flex justify-content-between flex-wrap gap-3">
        <!-- ***EVENT*** -->
        <div class="am-event d-flex p-4 justify-content-between" v-for="(card, index) in eventsArray" :key="index">
          <div class="d-flex flex-column align-self-center w-50"> 
            <h6><img src="../assets/geo-alt-fill.svg" alt="">{{card.location}}</h6>
            <h5>{{card.course}}</h5>
          </div>
         
          <div class="d-flex flex-column align-items-center">
            <h1>{{card.day}}</h1>
            <h5>{{card.month}}</h5>
            <button> Get ticket</button>
          </div>
        </div>
      </div>

      <div class="d-flex justify-content-around align-items-center mt-5">
        <div class="d-flex flex-column align-items-center">
          <h6>Ecited about our event? <span class="am-highlight-text"> View all events?</span></h6>
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
  padding-bottom: 15rem;
}

.am-event{
  width: 49%;
  margin-top: 2rem;
  background-color: #F8F8F8;
  border-radius: 7px;
}

h6{
  margin: 0;
  margin-bottom: 1rem;
}

img{
  margin-right: .3rem;
}

</style>