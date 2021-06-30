<template>

  <div class="layout startseite">

    <div class="startseiteInfoText">

      <div class="startseiteInfo">
        Integration-Kulturzentrum Kaleidoskop e.V<br><br>
      </div>

      <div>
        Sonntagsstudio wurde 2010 über ein Landesprojekt  ins Leben gerufen.<br><br> Seit 2002 ist Jugend in Jugendklub "Explosion"  als Jugendfreizeiteinrichtung durch die Stadt,JunOst e.V und DJO - deutsche Jugend in Europa gefördert.<br><br>

        Die aktive Beteiligung und Einbindung der Besucherinnen und Besucher, wie auch die interkulturelle Öffnung sind Querschnittsaufgaben und als solche in den Angeboten  verankert.<br><br>
      </div>

      <div>

        <div class="startseiteInfo">

          Sonntagsstudio-Angebote:<br><br>

        </div>

        <div>

          Freizeitpädagogische Angebote<br><br>
          Bewegungsangebot(Tanzen)<br><br>
          Kochangebot<br><br>
          Kreativangebot(Basteln,Musik)<br><br>
          Wochenendöffnungen<br><br>
          Ferienprogramme<br><br>

        </div>

        <div>

          <div class="startseiteInfo">

            Zielgruppen:

          </div>

          <div>

            Kinder und Jugendliche aller Nationalitäten und Kulturen<br><br>
            Eltern

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
  @import './../assets/styles/app.css';
  @import './../assets/styles/startseite.css';

</style>
