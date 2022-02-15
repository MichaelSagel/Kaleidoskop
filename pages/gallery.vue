<template>
  <nav class="nav">

      <div class="gallery-navbar">
                  
          <NuxtLink class="nav-button"
            to="/gallery" 
          >
            Auftritte
          </NuxtLink>
          
          <NuxtLink class="nav-button"
            to="/gallery/auszeichnungen" 
            >
            Auszeichnungen
          </NuxtLink>

                  
          <NuxtLink class="nav-button"
            to="/gallery/camps"
          >
            Camps
          </NuxtLink>

                  
          <NuxtLink class="nav-button"
            to="/gallery/dance"
          >
          Dance
          </NuxtLink>

                  
          <NuxtLink class="nav-button"
            to="/gallery/gesang"
          >
            Gesang
          </NuxtLink>

                  
          <NuxtLink class="nav-button"
            to="/gallery/kochmeister"
          >
            Kochmeister
          </NuxtLink>
                  
          <NuxtLink class="nav-button"
            to="/gallery/spielen"
          >
            Spielen
          </NuxtLink>

                  
          <NuxtLink class="nav-button"
            to="/gallery/silvester"
          >
            Silvester
          </NuxtLink>

                  
          <NuxtLink class="nav-button"
            to="/gallery/künstler"
          >
            Künstler
          </NuxtLink>

              
          <NuxtLink class="nav-button"
            to="/gallery/graffiti"
          >
            Graffiti Workshop
          </NuxtLink>
                  
                  
          <NuxtLink class="nav-button"
            to="/gallery/sonstige"
          >
            Sonstige
          </NuxtLink>

      </div>

      <div class="gallery-content">

          <Nuxt />

      </div>

  </nav>
</template>

<style>

  @import './../assets/styles/homepage.css';
  @import './../assets/styles/nav.css';

</style>

<script>
export default {
  head: {
    title: 'Galerie',
    meta: [
      {
        content: 'Galerie'
      }
    ],
  }
}
</script>