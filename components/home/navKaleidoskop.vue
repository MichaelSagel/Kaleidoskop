<template>
  <nav class="navigation">
    <NuxtLink
      to="/"
      class="navigation__image-wrapper"
    >
      <img src="./../../assets/images/romb.jpg" alt="Logo" class="navigation__image" >
    </NuxtLink>
    <div class="navigation__list">
      
      
      <NuxtLink
        to="/galerie" 
        class="button-bady navigation__list-item"
      >
        Galerie
      </NuxtLink>
      
      <NuxtLink
        to="/uber-uns"
        class="button-bady navigation__list-item"
      >
        Über uns
      </NuxtLink>

      <NuxtLink
          to="/partner" 
          class="button-bady navigation__list-item"
        >
          Partner
        </NuxtLink>

    </div>
  </nav>

</template>


<style>
@import './../../assets/styles/navKaleidoskop.css';
@import './../../assets/styles/login.css';
</style>
