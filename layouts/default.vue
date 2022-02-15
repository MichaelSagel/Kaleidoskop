<template>

  <div class="layout-body">

    <background/>

    <navbar/>

    <Nuxt/>

    <info/>

  </div>
</template>

<script>
  import navbar from '../components/home/navbar.vue';
  import info from './../components/home/info.vue';
  import background from './../components/home/background.vue';

  export default {
    components: {
      navbar,
      info,
      background,
    },
  };
</script>

<style>
@import './../assets/styles/global.css';
@import './../assets/styles/app.css';

</style>
