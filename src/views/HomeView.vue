<script setup>
    import Skills from '../../components/Skills.vue'
    import Int from '../../components/Interest.vue'
    import About from '../../components/About.vue'
    import Lang from '../../components/Lang.vue'
    import Qual from '../../components/Qualities.vue'
    import Head from '../../components/Header.vue'
    import Cont from '../../components/Content.vue'
</script>

<template>
  <main>
    <div class="container">
      <div class="left-column">
        <div class="img">
        <img class="" src="/public/images/noe.png" alt="photoNoeDelmas" width="125"></div>
        <About />
        <Skills />
        <Lang />
        <Int />
        <Qual />
        
      </div>
      <div class="right-column">
        <Head />
        <Cont />
      </div>
    </div>
  </main>
</template>
