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
#app {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
    }

section{
  padding-top: 3rem;
  padding-bottom: 3rem;
}
</style>
