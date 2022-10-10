<template>
  <div id="app">
    <HeaderComponent/>
    <JumbotronComponent/>
    <BuildDreamComponent/>
    <CoursesComponent/>
    <LearningComponent/>
    <EventsComponent/>
    <OpinionComponent/>
    <FooterComponent/>
    
  </div>
</template>

<script>
 import HeaderComponent from './components/HeaderComponent.vue';
import BuildDreamComponent from './components/BuildDreamComponent.vue';
import CoursesComponent from './components/CoursesComponent.vue';
import LearningComponent from './components/LearningComponent.vue';
import EventsComponent from './components/EventsComponent.vue';
import OpinionComponent from './components/OpinionComponent.vue';
import FooterComponent from './components/FooterComponent.vue';
import JumbotronComponent from './components/JumbotronComponent.vue';

export default {
  name: 'App',
  components: {
    HeaderComponent,
    BuildDreamComponent,
    CoursesComponent,
    LearningComponent,
    EventsComponent,
    OpinionComponent,
    FooterComponent,
    JumbotronComponent
}
}
</script>

<style lang="scss">

  @import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,400;0,500;0,700;0,800;0,900;1,300;1,400;1,500;1,700;1,800;1,900&display=swap');

#app {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  font-family: 'Poppins', sans-serif;
    }

section{
  padding-top: 2rem;
  padding-bottom: 2rem;
}

h1{
  font-weight: 600 !important;
}
</style>
