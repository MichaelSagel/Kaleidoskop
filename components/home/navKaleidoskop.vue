<template>
  <nav class="navigation">
    <NuxtLink
      to="/"
    >
      <img src="./../../assets/images/romb.jpg" alt="Logo" class="navigation__image" >
    </NuxtLink>

    <div 
      class="navigation__list"
    >      
      <NuxtLink
        to="/gallery" 
        class="navigation__list-item"
      >
        Galerie
      </NuxtLink>
      
      <NuxtLink
        to="/uber-uns"
        class="navigation__list-item"
      >
        Über uns
      </NuxtLink>

      <NuxtLink
          to="/partner" 
          class="navigation__list-item"
        >
          Partner
        </NuxtLink>
    </div>

    <a
      href="https://www.instagram.com/olgagart_kaleidoskop/"
      target=“_blank“
      rel=“noopener“
    >
      <img src="./../../assets/images/instagram.png" alt="Logo" class="instagram_image" >
    </a>

  </nav>

</template>


<style>
@import './../../assets/styles/navKaleidoskop.css';
</style>
