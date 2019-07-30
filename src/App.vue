<template>
  <div id="app" class="antialiased">
    <Nav />
    
    <Intro />
    
    <Rotator />

    <Advices />

    <DictionaryForm />

    <Footer />
    <Credits />
  </div>
</template>

<script>
import Nav from './components/Nav.vue'
import Intro from './components/Intro.vue'
import Rotator from './components/Rotator.vue'
import Advices from './components/Advices.vue'
import DictionaryForm from './components/DictionaryForm.vue'
import Footer from './components/Footer.vue'
import Credits from './components/Credits.vue'

export default {
  name: 'app',
  components: {
    Nav,
    Intro,
    Rotator,
    Advices,
    DictionaryForm,
    Footer,
    Credits
  }
}
</script>

<style lang="scss">

</style>
