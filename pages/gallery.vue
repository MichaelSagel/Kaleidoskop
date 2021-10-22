<template>
  <nav class="nav">

      <div class="navBar">
                  
          <NuxtLink class="navButton"
            to="/gallery" 
          >
            Auftritte
          </NuxtLink>
          
          <NuxtLink class="navButton"
            to="/gallery/auszeichnungen" 
            >
            Auszeichnungen
          </NuxtLink>

                  
          <NuxtLink class="navButton"
            to="/gallery/camps"
          >
            Camps
          </NuxtLink>

                  
          <NuxtLink class="navButton"
            to="/gallery/dance"
          >
          Dance
          </NuxtLink>

                  
          <NuxtLink class="navButton"
            to="/gallery/gesang"
          >
            Gesang
          </NuxtLink>

                  
          <NuxtLink class="navButton"
            to="/gallery/kochmeister"
          >
            Kochmeister
          </NuxtLink>
                  
          <NuxtLink class="navButton"
            to="/gallery/spielen"
          >
            Spielen
          </NuxtLink>

                  
          <NuxtLink class="navButton"
            to="/gallery/silvester"
          >
            Silvester
          </NuxtLink>

                  
          <NuxtLink class="navButton"
            to="/gallery/künstler"
          >
            Künstler
          </NuxtLink>

              
          <NuxtLink class="navButton"
            to="/gallery/graffiti"
          >
            Graffiti Workshop
          </NuxtLink>
                  
                  
          <NuxtLink class="navButton"
            to="/gallery/sonstige"
          >
            Sonstige
          </NuxtLink>

      </div>

      <div>

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
        hid: 'description',
        name: 'description',
        content: 'Galerie'
      }
    ],
  }
}
</script>