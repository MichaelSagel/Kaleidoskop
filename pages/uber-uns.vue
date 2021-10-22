<template>

    <div class="homepage">

        <h1
            class="h1"
        >
            Kaleidoskop-Team
        </h1>

        <div class="homepageHeader">

            <div class="homepageInfoText">

                <div class="homepageInfoDescription">Unsere Referentienen und Referenten engagieren sich seit Jahren</div>  
                <div class="homepageInfoDescription">in der internationalen Jugendarbeit in Deutschland.</div>
                <div class="homepageInfoDescription">Sie haben eine große Erfahrung als Lehrkraft, Referenten und Fachkraft,</div>
                <div>die sie durch  ehrenamtliches Engagement verstärken.</div>

            </div>

        </div>    


            <div class="team teamMargin">

                <div class="teamMember homepageInfoText">

                    <div class="homepageInfoDescription">Olga Gart</div>

                    <div>Leiterin und Integrationreferentin</div>

                    <img src="./../assets/images/leiterin.jpg" class="teamImg">

                </div>

                <div class="teamMember homepageInfoText">

                    <div class="homepageInfoDescription">Nadeschda Loos</div>

                    <div>Verwaltungsreferentin</div>

                    <img src="./../assets/images/nadja.jpg" class="teamImg">

                </div>

                <div class="teamMember homepageInfoText">

                    <div class="homepageInfoDescription">Scheuermann</div>

                    <div>Bastelnreferentin</div>

                    <img src="./../assets/images/nadjamaman.jpg" class="teamImg">

                </div>

            </div>

            <div class="team teamMargin">

                <div class="teamMember homepageInfoText">

                    <div class="homepageInfoDescription">Anastasiya Kaptsiuh</div>

                    <div>Tanzreferentin</div>

                    <img src="./../assets/images/tanzreferentin.jpg" class="teamImg">

                </div>

                <div class="teamMember homepageInfoText">

                    <div class="homepageInfoDescription">Luisa Badronova</div>

                    <div>Tanzreferentin</div>

                    <img src="./../assets/images/luisa.jpg" class="teamImg">

                </div>

                <div class="teamMember homepageInfoText">

                    <div class="homepageInfoDescription">Maria Hofman und Nicole Schmid</div>

                    <div>Tanzreferentinen</div>

                    <img src="./../assets/images/tanzreferentinen.jpg" class="teamImg">

                </div>


            </div>

        <div class="projekt homepageInfoText">

            <div class="team">

                Projekt Team
                
            </div>

            <div class="team">

                <div class=" homepageInfoText">

                    <img src="./../assets/images/artur.jpg" class="projektImg">

                    <img src="./../assets/images/anfisa.png" class="projektImg">

                    <img src="./../assets/images/lt.png" class="projektImg">

                    <img src="./../assets/images/mams.png" class="projektImg">

                </div>

            </div>

        </div>

    </div>

</template>

<style>

  @import './../assets/styles/homepage.css';
  @import './../assets/styles/nav.css';
  @import './../assets/styles/team.css';

</style>

<script>
export default {
  head: {
    title: 'Über uns',
    meta: [
      {
        hid: 'description',
        name: 'description',
        content: 'Über uns'
      }
    ],
  }
}
</script>