<template>

  <div class="layout-body">

    <background/>

    <navKaleidoskop/>

    <Nuxt />

    <info/>

  </div>
</template>

<script>
  import navKaleidoskop from './../components/home/navKaleidoskop.vue';
  import info from './../components/home/info.vue';
  import background from './../components/home/background.vue';

  export default {
    components: {
      navKaleidoskop,
      info,
      background,
    },
  };
</script>

<style>
@import './../assets/styles/global.css';
@import './../assets/styles/app.css';

</style>
