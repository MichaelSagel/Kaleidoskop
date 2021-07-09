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
            { image: require('./../../assets/photos/auszeichnungen/auszeichnungen1.jpg') },
            { image: require('./../../assets/photos/auszeichnungen/auszeichnungen2.png') },
            { image: require('./../../assets/photos/auszeichnungen/auszeichnungen3.png') },
            { image: require('./../../assets/photos/auszeichnungen/auszeichnungen4.png') },
            { image: require('./../../assets/photos/auszeichnungen/auszeichnungen5.png') },
            { image: require('./../../assets/photos/auszeichnungen/auszeichnungen6.jpg') },
           
        ]
        })

    }

</script>



<style>

     @import './../../assets/styles/galerie.css';

</style>