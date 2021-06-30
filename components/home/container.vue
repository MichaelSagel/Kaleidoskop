<template>
  <div class="container">
    <div class="container-bady">
      <login/>

      <containerBodyText/>

      <mail/>

      <password/>

      <forgotPassword/>

      <containerBodyButton/>
    </div>
  </div>
</template>

<script>

import containerBodyText from './containerBodyText.vue';
import mail from './mail.vue';
import password from './password.vue';
import login from './login.vue';
import forgotPassword from './forgotPassword.vue';
import containerBodyButton from './containerBodyButton.vue';

/*
  import containerBodyButton from './containerBodyButton.vue'
  */

export default {

  auth: false,

  components: {
    containerBodyText,
    mail,
    password,
    login,
    forgotPassword,
    containerBodyButton,
  },
};

</script>

<style>

  @import './../../assets/styles/container.css';

</style>
