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
            { image: require('./../../assets/photos/graffiti/graffiti1.jpg') },
            { image: require('./../../assets/photos/graffiti/graffiti2.jpg') },
            { image: require('./../../assets/photos/graffiti/graffiti3.jpg') },
            { image: require('./../../assets/photos/graffiti/graffiti4.jpg') },
            { image: require('./../../assets/photos/graffiti/graffiti5.jpg') },
            { image: require('./../../assets/photos/graffiti/graffiti6.jpg') },
            { image: require('./../../assets/photos/graffiti/graffiti7.jpg') },
            { image: require('./../../assets/photos/graffiti/graffiti8.jpg') },
            { image: require('./../../assets/photos/graffiti/graffiti9.jpg') },
            { image: require('./../../assets/photos/graffiti/graffiti10.jpg') },
            { image: require('./../../assets/photos/graffiti/graffiti11.jpg') },
            { image: require('./../../assets/photos/graffiti/graffiti12.jpg') },
            { image: require('./../../assets/photos/graffiti/graffiti13.jpg') },
            { image: require('./../../assets/photos/graffiti/graffiti14.jpg') },
            { image: require('./../../assets/photos/graffiti/graffiti15.jpg') },
            { image: require('./../../assets/photos/graffiti/graffiti16.jpg') },
            { image: require('./../../assets/photos/graffiti/graffiti17.jpg') },
            { image: require('./../../assets/photos/graffiti/graffiti18.jpg') },
            { image: require('./../../assets/photos/graffiti/graffiti19.jpg') },
            { image: require('./../../assets/photos/graffiti/graffiti20.jpg') },
            { image: require('./../../assets/photos/graffiti/graffiti21.jpg') },
            { image: require('./../../assets/photos/graffiti/graffiti22.jpg') },
            { image: require('./../../assets/photos/graffiti/graffiti23.jpg') },
            { image: require('./../../assets/photos/graffiti/graffiti24.jpg') },
            { image: require('./../../assets/photos/graffiti/graffiti25.jpg') },
            { image: require('./../../assets/photos/graffiti/graffiti26.jpg') },
            { image: require('./../../assets/photos/graffiti/graffiti27.jpg') },
        ]
        })

    }

</script>



<style>

     @import './../../assets/styles/galerie.css';

</style>
