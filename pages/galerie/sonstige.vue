<template>

   <div class="galerieContainer">

       <div class="photoContainer">
                
        <vueper-slides :slide-ratio="1 / 2" fixed-height="600px">
        <vueper-slide v-for="(slide, i) in slides" :key="i" :image="slide.image" />
        </vueper-slides>

       </div>

   </div>

</template>


<script>

    import { VueperSlides, VueperSlide } from 'vueperslides'
    import 'vueperslides/dist/vueperslides.css'

    export default {
    components: { VueperSlides, VueperSlide },
  
    data: () => ({
        slides: [
            { image: require('./../../assets/photos/sonstige/sonstige1.jpg') },
            { image: require('./../../assets/photos/sonstige/sonstige2.jpg') },
            { image: require('./../../assets/photos/sonstige/sonstige3.png') },
            { image: require('./../../assets/photos/sonstige/sonstige4.jpg') },
            { image: require('./../../assets/photos/sonstige/sonstige5.jpg') },
            { image: require('./../../assets/photos/sonstige/sonstige6.jpg') },
            { image: require('./../../assets/photos/sonstige/sonstige7.jpg') },
            { image: require('./../../assets/photos/sonstige/sonstige8.png') },
            { image: require('./../../assets/photos/sonstige/sonstige9.png') },
            { image: require('./../../assets/photos/sonstige/sonstige10.png') },
            { image: require('./../../assets/photos/sonstige/sonstige11.png') },
            { image: require('./../../assets/photos/sonstige/sonstige12.png') },
            { image: require('./../../assets/photos/sonstige/sonstige13.png') },
            { image: require('./../../assets/photos/sonstige/sonstige14.png') },
            { image: require('./../../assets/photos/sonstige/sonstige15.png') },
            { image: require('./../../assets/photos/sonstige/sonstige16.png') },
            { image: require('./../../assets/photos/sonstige/sonstige17.png') },
            { image: require('./../../assets/photos/sonstige/sonstige18.png') },
            { image: require('./../../assets/photos/sonstige/sonstige19.png') },
            { image: require('./../../assets/photos/sonstige/sonstige20.png') },
            { image: require('./../../assets/photos/sonstige/sonstige21.png') },
            { image: require('./../../assets/photos/sonstige/sonstige22.png') },
            { image: require('./../../assets/photos/sonstige/sonstige23.png') },
            { image: require('./../../assets/photos/sonstige/sonstige24.png') },
            { image: require('./../../assets/photos/sonstige/sonstige25.png') },
            { image: require('./../../assets/photos/sonstige/sonstige26.jpg') },
            { image: require('./../../assets/photos/sonstige/sonstige27.jpg') },
            { image: require('./../../assets/photos/sonstige/sonstige28.jpg') },
            { image: require('./../../assets/photos/sonstige/sonstige29.jpg') },
            { image: require('./../../assets/photos/sonstige/sonstige30.jpg') },
            { image: require('./../../assets/photos/sonstige/sonstige31.jpg') },
            { image: require('./../../assets/photos/sonstige/sonstige32.jpg') },
            { image: require('./../../assets/photos/sonstige/sonstige33.jpg') },
            { image: require('./../../assets/photos/sonstige/sonstige34.jpg') },
            { image: require('./../../assets/photos/sonstige/sonstige35.jpg') },
            { image: require('./../../assets/photos/sonstige/sonstige36.jpg') },
            { image: require('./../../assets/photos/sonstige/sonstige37.jpg') },
            { image: require('./../../assets/photos/sonstige/sonstige38.jpg') },
            { image: require('./../../assets/photos/sonstige/sonstige39.jpg') },
            { image: require('./../../assets/photos/sonstige/sonstige40.jpg') },
            { image: require('./../../assets/photos/sonstige/sonstige41.jpg') },
            { image: require('./../../assets/photos/sonstige/sonstige42.jpg') },
            { image: require('./../../assets/photos/sonstige/sonstige43.jpg') },
            { image: require('./../../assets/photos/sonstige/sonstige44.jpg') },
            { image: require('./../../assets/photos/sonstige/sonstige45.jpg') },
            { image: require('./../../assets/photos/sonstige/sonstige46.jpg') },
            { image: require('./../../assets/photos/sonstige/sonstige47.jpg') },
            { image: require('./../../assets/photos/sonstige/sonstige48.jpg') },
            { image: require('./../../assets/photos/sonstige/sonstige49.jpg') },
            { image: require('./../../assets/photos/sonstige/sonstige50.jpg') },
            { image: require('./../../assets/photos/sonstige/sonstige52.jpg') },
        ]
        })

    }

</script>



<style>

     @import './../../assets/styles/galerie.css';

</style>
