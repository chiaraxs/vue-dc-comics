<template>
  <div id="app">
    
    <header-box />
    <hero-box />
    <main-content />
    <section-shop />
    <footer-box />
    <section-contacts />

  </div>
</template>

<script>
import HeaderBox from './components/HeaderBox.vue'
import HeroBox from './components/HeroBox.vue'
import MainContent from './components/MainContent.vue'
import SectionShop from './components/SectionShop.vue'
import FooterBox from './components/FooterBox.vue'
import SectionContacts from './components/SectionContacts.vue'

export default {
  name: 'App',
  components: {
    HeaderBox,
    HeroBox,
    MainContent,
    SectionShop,
    FooterBox,
    SectionContacts,
  }
}
</script>

<style lang="scss">
@import './style/common.scss';
@import url('https://fonts.googleapis.com/css2?family=Roboto&display=swap');

</style>
