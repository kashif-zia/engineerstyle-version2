<template>
  <Header />
  <main>
    <HeroSection />
    <ManOfAbility />
    <Strength />
    <VoiceOfAchievers />
    <ProjectSummary />
    <ServiceProcess />
    <FAQ />
    <WhatStyleKunSection />
  </main>
  <FooterSection />
</template>


<script>
import Header from '../components/Header.vue'
import HeroSection from '../components/HeroSection.vue'
import ManOfAbility from '../components/ManAbility.vue';
import Strength from '../components/Strength.vue';
import VoiceOfAchievers from '../components/VoiceOfAchievers.vue';
import ProjectSummary from '../components/ProjectSummary.vue';
import ServiceProcess from '../components/ServiceProcess.vue';
import FAQ from '../components/FAQ.vue';
import WhatStyleKunSection from '../components/WhatStyleKunSection.vue';
import FooterSection from '../components/FooterSection.vue'
export default {
  components: {
    Header,
    HeroSection,
    ManOfAbility,
    Strength,
    VoiceOfAchievers,
    ProjectSummary,
    ServiceProcess,
    FAQ,
    WhatStyleKunSection,
    FooterSection
  }
}
</script>