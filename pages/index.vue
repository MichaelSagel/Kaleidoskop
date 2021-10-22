<template>

  <div 
    class="homepage"
  >

    <div 
      class="homepageInfoText"
    >

      <h1 
        class="homepageInfo"
      >
        Integration-Kulturzentrum Kaleidoskop e.V
      </h1>

      <div 
        class="homepageInfoDescription"
      >
        Sonntagsstudio wurde 2010 über ein Landesprojekt  ins Leben gerufen.
      </div>

      <div 
        class="homepageInfoDescription"
      >
        Seit 2002 ist Jugend in Jugendklub "Explosion"  als Jugendfreizeiteinrichtung durch die Stadt,
      </div>

      <div 
        class="homepageInfoDescription"
      >
        JunOst e.V und DJO - deutsche Jugend in Europa gefördert.
      </div>

      <div 
        class="homepageInfoDescriptionInfo"
      >
        <div 
          class="homepageInfoDescription"
        >
          Die aktive Beteiligung und Einbindung der Besucherinnen und Besucher,
          </div>

        <div 
          class="homepageInfoDescription"
        >
          wie auch die interkulturelle Öffnung sind Querschnittsaufgaben und als solche in den Angeboten  verankert.<br><br>
        </div>
      </div>

      <div>

        <div 
          class="homepageInfo"
        >
          Sonntagsstudio-Angebote:
        </div>

        <div
          class="homepageInfoOffers"
        >
          Freizeitpädagogische Angebote
        </div>

        <div
          class="homepageInfoOffers"
        >
          Bewegungsangebot(Tanzen)
        </div>

        <div
          class="homepageInfoOffers"
        >
          Kochangebot
        </div>

        <div
          class="homepageInfoOffers"
        >
          Kreativangebot(Basteln,Musik)
        </div>

        <div
          class="homepageInfoOffers"
        >
          Wochenendöffnungen
        </div>

        <div
          class="homepageInfoOffers"
        >
          Ferienprogramme
        </div>

        <div>

          <div 
            class="homepageInfo"
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
