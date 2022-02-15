<template>
  <nav class="navbar">
    <NuxtLink
      to="/"
    >
      <img src="./../../assets/images/romb.jpg" alt="Logo" class="navbar__image" >
    </NuxtLink>

    <div 
      class="navbar__list"
    >      
      <NuxtLink
        to="/gallery" 
        class="navbar__list-item"
      >
        Galerie
      </NuxtLink>
      
      <NuxtLink
        to="/uber-uns"
        class="navbar__list-item"
      >
        Über uns
      </NuxtLink>

      <NuxtLink
          to="/partner" 
          class="navbar__list-item"
        >
          Partner
        </NuxtLink>
    </div>

    <a
      href="https://www.instagram.com/olgagart_kaleidoskop/"
      target=“_blank“
      rel=“noopener“
    >
      <img src="./../../assets/images/instagram.png" alt="Logo" class="instagram__image" >
    </a>

  </nav>

</template>


<style>
@import './../../assets/styles/navbar.css';
</style>
