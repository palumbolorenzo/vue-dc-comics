<template>
  <div>
    <HeaderPage />
    <SectionBlack />
    <MainPage />
    <SectionBlue />
    <FooterPage />
    <FooterLinks />
  </div>
</template>

<script>
import HeaderPage from '@/components/HeaderPage.vue';
import SectionBlack from '@/components/SectionBlack.vue';
import MainPage from '@/components/MainPage.vue';
import SectionBlue from '@/components/SectionBlue.vue';
import FooterPage from '@/components/FooterPage.vue';
import FooterLinks from '@/components/FooterLinks.vue';

export default {
  components: {
    HeaderPage,
    SectionBlack,
    MainPage,
    SectionBlue,
    FooterPage,
    FooterLinks
  }
}
</script>

<style>
 *{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
 }

 html {
  font-family: sans-serif;
 }
</style>