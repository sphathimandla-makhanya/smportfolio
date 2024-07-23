<template>
  <div class="home">
    <LandingComp/>
    <AboutComp/>
    <ResumeComp/>
    <ProjectsComp/>
    <ContactComp/>
  </div>
</template>

<script>
import LandingComp from '@/components/LandingComp.vue';
import AboutComp from '@/components/AboutComp.vue';
import ResumeComp from '@/components/ResumeComp.vue';
import ProjectsComp from '@/components/ProjectsComp.vue';
import ContactComp from '@/components/ContactComp.vue'
export default {
  components: { 
    LandingComp,
    AboutComp,
    ResumeComp,
    ProjectsComp,
    ContactComp
  }
}
</script>

<style>
</style>
