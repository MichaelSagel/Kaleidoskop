<template>

  <div>

  <script type="application/ld+json">
    {
      "@context": "https://schema.org",
      "@type": "Organization",
      "logo": "./../assets/styles/logo.css",
      "image": "./../assets/images/hands.jpg",
      "description": "Sonntagsstudio ist ein Landesprojekt. Jugendklub \"Explosion\" ist Jugendfreizeiteinrichtung, JunOst e.V und DJO.",
      "email": "Ikz_kaleidoskop@yahoo.com",
      "name": "Integration-Kulturzentrum Kaleidoskop e.V",
      "address": {
        "@type": "PostalAddress",
        "streetAddress": "Am Stadtwald 6d",
        "addressLocality": "Offenburg",
        "addressRegion": "OG",
        "postalCode": "77656",
        "addressCountry": "DE"
      },
      "geo": {
        "@type": "GeoCoordinates",
        "latitude": 48.46097102588812,
        "longitude": 7.921246516611682
      },
      "url": "http://kaleidoskop-og.de/",
      "telephone": "07819672807",
      "openingHoursSpecification": [
        {
          "@type": "OpeningHoursSpecification",
          "dayOfWeek": "Sunday",
          "opens": "16:00",
          "closes": "22:00"
        }
      ]
    }
  </script>
  <div class="layout-body">

    <background/>

    <navKaleidoskop/>

    <Nuxt />

    <info/>

  </div>
  </div>
</template>

<script>
  import navKaleidoskop from './../components/home/navKaleidoskop.vue';
  import info from './../components/home/info.vue';
  import background from './../components/home/background.vue';

  export default {
    components: {
      navKaleidoskop,
      info,
      background,
    },
  };
</script>

<style>
@import './../assets/styles/global.css';
@import './../assets/styles/app.css';

</style>
