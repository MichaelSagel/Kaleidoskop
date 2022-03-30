<template>

  <div 
    class="homepage"
  >

    <div 
      class="homepage-info__text"
    >

      <h1 
        class="homepage-info"
      >
        Integration-Kulturzentrum Kaleidoskop e.V
      </h1>

      <div 
        class="homepage-info-description"
      >
        Sonntagsstudio wurde 2010 über ein Landesprojekt  ins Leben gerufen.
      </div>

      <div 
        class="homepage-info-description"
      >
        Seit 2002 ist Jugend in Jugendklub "Explosion"  als Jugendfreizeiteinrichtung durch die Stadt,
      </div>

      <div 
        class="homepage-info-description"
      >
        JunOst e.V und DJO - deutsche Jugend in Europa gefördert.
      </div>

      <div 
        class="homepage-info-description"
      >
        <div 
          class="homepage-info-description"
        >
          Die aktive Beteiligung und Einbindung der Besucherinnen und Besucher,
          </div>

        <div 
          class="homepage-info-description"
        >
          wie auch die interkulturelle Öffnung sind Querschnittsaufgaben und als solche in den Angeboten  verankert.<br><br>
        </div>
      </div>

      <div>

        <div 
          class="homepage-info"
        >
          Sonntagsstudio-Angebote:
        </div>

        <div
          class="homepage-info-offers"
        >
          Freizeitpädagogische Angebote
        </div>

        <div
          class="homepage-info-offers"
        >
          Bewegungsangebot(Tanzen)
        </div>

        <div
          class="homepage-info-offers"
        >
          Kochangebot
        </div>

        <div
          class="homepage-info-offers"
        >
          Kreativangebot(Basteln,Musik)
        </div>

        <div
          class="homepage-info-offers"
        >
          Wochenendöffnungen
        </div>

        <div
          class="homepage-info-offers"
        >
          Ferienprogramme
        </div>

        <div>

          <div 
            class="homepage-info"
          >
            Zielgruppen:
          </div>

          <div>
            Kinder und Jugendliche aller Nationalitäten und Kulturen Eltern
          </div>

        </div>

      </div>

    </div>

    <Nuxt />

  </div>
</template>

<script>

    import logo from './../components/home/logo.vue';

export default {

    auth: false,

  components: {
    logo,
  },
};

</script>

<style>

  @import './../assets/styles/global.css';
  @import './../assets/styles/homepage.css';

</style>
