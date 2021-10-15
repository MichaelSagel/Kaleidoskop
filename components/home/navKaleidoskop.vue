<template>
  <nav class="navigation">
    <NuxtLink
      to="/"
    >
      <img src="./../../assets/images/romb.jpg" alt="Logo" class="navigation__image" >
    </NuxtLink>
    <div class="navigation__list">
      
      
      <NuxtLink
        to="/gallery" 
        class="button-body navigation__list-item"
      >
        Galerie
      </NuxtLink>
      
      <NuxtLink
        to="/uber-uns"
        class="button-body navigation__list-item"
      >
        Über uns
      </NuxtLink>

      <NuxtLink
          to="/partner" 
          class="button-body navigation__list-item"
        >
          Partner
        </NuxtLink>

    </div>
  </nav>

</template>


<style>
@import './../../assets/styles/navKaleidoskop.css';
</style>
