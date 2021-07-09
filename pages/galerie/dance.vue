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
            { image: require('./../../assets/photos/dance/dance1.png') },
            { image: require('./../../assets/photos/dance/dance2.png') },
            { image: require('./../../assets/photos/dance/dance3.jpg') },
            { image: require('./../../assets/photos/dance/dance4.jpg') },
            { image: require('./../../assets/photos/dance/dance5.jpg') },
            { image: require('./../../assets/photos/dance/dance6.jpg') },
            { image: require('./../../assets/photos/dance/dance7.jpg') },
            { image: require('./../../assets/photos/dance/dance8.jpg') },
            { image: require('./../../assets/photos/dance/dance9.jpg') },
            { image: require('./../../assets/photos/dance/dance10.jpg') },
            { image: require('./../../assets/photos/dance/dance11.jpg') },
            { image: require('./../../assets/photos/dance/dance12.jpg') },
            { image: require('./../../assets/photos/dance/dance13.jpg') },
            { image: require('./../../assets/photos/dance/dance14.jpg') },
            { image: require('./../../assets/photos/dance/dance15.jpg') },
            { image: require('./../../assets/photos/dance/dance16.jpg') },
            { image: require('./../../assets/photos/dance/dance17.jpg') },
            { image: require('./../../assets/photos/dance/dance18.jpg') },
            { image: require('./../../assets/photos/dance/dance19.jpg') },
            { image: require('./../../assets/photos/dance/dance20.jpg') },
            { image: require('./../../assets/photos/dance/dance21.jpg') },
            { image: require('./../../assets/photos/dance/dance22.jpg') },
            { image: require('./../../assets/photos/dance/dance23.jpg') },
            { image: require('./../../assets/photos/dance/dance24.jpg') },
            { image: require('./../../assets/photos/dance/dance25.jpg') },
            { image: require('./../../assets/photos/dance/dance26.jpg') },
            { image: require('./../../assets/photos/dance/dance27.jpg') },
            { image: require('./../../assets/photos/dance/dance28.jpg') },
            { image: require('./../../assets/photos/dance/dance29.jpg') },
            { image: require('./../../assets/photos/dance/dance30.jpg') },
            { image: require('./../../assets/photos/dance/dance31.jpg') },
            { image: require('./../../assets/photos/dance/dance32.jpg') },
            { image: require('./../../assets/photos/dance/dance33.jpg') },
            { image: require('./../../assets/photos/dance/dance34.jpg') },
            { image: require('./../../assets/photos/dance/dance35.jpg') },
            { image: require('./../../assets/photos/dance/dance36.jpg') },
            { image: require('./../../assets/photos/dance/dance37.jpg') },
            { image: require('./../../assets/photos/dance/dance38.jpg') },
            { image: require('./../../assets/photos/dance/dance39.jpg') },
            { image: require('./../../assets/photos/dance/dance40.jpg') },
            { image: require('./../../assets/photos/dance/dance41.jpg') },
            { image: require('./../../assets/photos/dance/dance42.jpg') },
            { image: require('./../../assets/photos/dance/dance43.jpg') },
            { image: require('./../../assets/photos/dance/dance44.jpg') },
            { image: require('./../../assets/photos/dance/dance45.jpg') },
            { image: require('./../../assets/photos/dance/dance46.jpg') },
            { image: require('./../../assets/photos/dance/dance47.jpg') },
            { image: require('./../../assets/photos/dance/dance48.jpg') },
            { image: require('./../../assets/photos/dance/dance49.jpg') },
            { image: require('./../../assets/photos/dance/dance50.jpg') },
            { image: require('./../../assets/photos/dance/dance51.jpg') },
            { image: require('./../../assets/photos/dance/dance52.jpg') },
            { image: require('./../../assets/photos/dance/dance53.jpg') },
            { image: require('./../../assets/photos/dance/dance54.jpg') },
            { image: require('./../../assets/photos/dance/dance55.jpg') },
            { image: require('./../../assets/photos/dance/dance56.jpg') },
            { image: require('./../../assets/photos/dance/dance57.jpg') },
            { image: require('./../../assets/photos/dance/dance58.jpg') },
            { image: require('./../../assets/photos/dance/dance59.jpg') },
            { image: require('./../../assets/photos/dance/dance60.jpg') },
            { image: require('./../../assets/photos/dance/dance61.jpg') },
            { image: require('./../../assets/photos/dance/dance62.jpg') },
            { image: require('./../../assets/photos/dance/dance63.jpg') },
            { image: require('./../../assets/photos/dance/dance64.jpg') },
            { image: require('./../../assets/photos/dance/dance65.jpg') },
            { image: require('./../../assets/photos/dance/dance66.jpg') },
            { image: require('./../../assets/photos/dance/dance67.jpg') },
            { image: require('./../../assets/photos/dance/dance68.jpg') },
            { image: require('./../../assets/photos/dance/dance69.jpg') },
            { image: require('./../../assets/photos/dance/dance70.jpg') },
            { image: require('./../../assets/photos/dance/dance71.jpg') },
            { image: require('./../../assets/photos/dance/dance72.jpg') },
        ]
        })

    }

</script>



<style>

     @import './../../assets/styles/galerie.css';

</style>
