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
        to="/Sonntagskoffer"
        class="button-bady navigation__list-item"
      >
        Sonntagskoffer
      </NuxtLink>
      <NuxtLink
        to="/termine"
        class="button-bady navigation__list-item"
      >
        Termine
      </NuxtLink>
      <NuxtLink
        to="/galerie" 
        class="button-bady navigation__list-item"
      >
        Galerie
      </NuxtLink>
      <NuxtLink
        to="/angebote" 
        class="button-bady navigation__list-item"
      >
        Angebote
      </NuxtLink>
      <NuxtLink
        to="/überUns"
        class="button-bady navigation__list-item"
      >
        Über uns
      </NuxtLink>
    
    </div>
  </nav>

</template>


<style>
@import './../../assets/styles/navKaleidoskop.css';
@import './../../assets/styles/login.css';
</style>
