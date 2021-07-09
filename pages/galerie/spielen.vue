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
            { image: require('./../../assets/photos/spielen/spielen1.jpg') },
            { image: require('./../../assets/photos/spielen/spielen2.jpg') },
            { image: require('./../../assets/photos/spielen/spielen3.jpg') },
            { image: require('./../../assets/photos/spielen/spielen4.jpg') },
            { image: require('./../../assets/photos/spielen/spielen5.jpg') },
            { image: require('./../../assets/photos/spielen/spielen6.jpg') },
            { image: require('./../../assets/photos/spielen/spielen7.jpg') },
            { image: require('./../../assets/photos/spielen/spielen8.jpg') },
            { image: require('./../../assets/photos/spielen/spielen9.jpg') },
            { image: require('./../../assets/photos/spielen/spielen10.jpg') },
            { image: require('./../../assets/photos/spielen/spielen11.jpg') },
            { image: require('./../../assets/photos/spielen/spielen12.jpg') },
            { image: require('./../../assets/photos/spielen/spielen13.jpg') },
            { image: require('./../../assets/photos/spielen/spielen14.jpg') },
            { image: require('./../../assets/photos/spielen/spielen15.jpg') },
            { image: require('./../../assets/photos/spielen/spielen16.jpg') },
            { image: require('./../../assets/photos/spielen/spielen17.jpg') },
            { image: require('./../../assets/photos/spielen/spielen18.jpg') },
            { image: require('./../../assets/photos/spielen/spielen19.jpg') },
            { image: require('./../../assets/photos/spielen/spielen21.jpg') },
            { image: require('./../../assets/photos/spielen/spielen22.jpg') },
            { image: require('./../../assets/photos/spielen/spielen23.jpg') },
            { image: require('./../../assets/photos/spielen/spielen24.jpg') },
            { image: require('./../../assets/photos/spielen/spielen25.jpg') },
            { image: require('./../../assets/photos/spielen/spielen26.jpg') },
            { image: require('./../../assets/photos/spielen/spielen27.jpg') },
            { image: require('./../../assets/photos/spielen/spielen28.jpg') },
            { image: require('./../../assets/photos/spielen/spielen29.jpg') },
            { image: require('./../../assets/photos/spielen/spielen30.jpg') },
            { image: require('./../../assets/photos/spielen/spielen31.jpg') },
            { image: require('./../../assets/photos/spielen/spielen32.jpg') },
            { image: require('./../../assets/photos/spielen/spielen33.jpg') },
            { image: require('./../../assets/photos/spielen/spielen34.jpg') },
            { image: require('./../../assets/photos/spielen/spielen35.jpg') },
            { image: require('./../../assets/photos/spielen/spielen36.jpg') },
            { image: require('./../../assets/photos/spielen/spielen37.jpg') },
            { image: require('./../../assets/photos/spielen/spielen38.jpg') },
            { image: require('./../../assets/photos/spielen/spielen39.jpg') },
            { image: require('./../../assets/photos/spielen/spielen40.jpg') },
            { image: require('./../../assets/photos/spielen/spielen41.jpg') },
            { image: require('./../../assets/photos/spielen/spielen42.jpg') },
            { image: require('./../../assets/photos/spielen/spielen43.jpg') },
            { image: require('./../../assets/photos/spielen/spielen44.jpg') },
            { image: require('./../../assets/photos/spielen/spielen45.jpg') },
            { image: require('./../../assets/photos/spielen/spielen46.jpg') },
        ]
        })

    }

</script>



<style>

     @import './../../assets/styles/galerie.css';

</style>
