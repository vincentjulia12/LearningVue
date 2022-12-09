<template>
  <div>
    <NavBarComponent />
    <RouterView />
    <AboutView />
    <footerComponent />
  </div>
  
</template>

<script>

/* eslint-disable */
import NavBarComponent from "./components/NavBarComponent.vue";
import FooterComponent from './components/FooterComponent.vue';


export default {
  name: 'App',
  components: {
    NavBarComponent,
    FooterComponent
  },
};
</script>

<style lang="scss">
@import "./style/main.scss";
@import "./style/faq.scss";
@import "./style/navbar.scss";

</style>
