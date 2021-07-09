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
            { image: require('./../../assets/photos/kochmeister/kochmeister1.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister2.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister3.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister4.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister5.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister6.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister7.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister8.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister9.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister10.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister11.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister12.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister13.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister14.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister15.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister16.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister17.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister18.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister19.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister20.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister21.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister22.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister23.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister24.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister25.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister26.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister27.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister28.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister29.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister30.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister31.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister32.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister33.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister34.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister35.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister36.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister37.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister38.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister39.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister40.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister41.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister42.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister43.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister44.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister45.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister46.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister47.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister48.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister49.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister50.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister51.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister52.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister53.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister54.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister55.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister56.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister57.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister58.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister59.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister60.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister61.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister62.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister63.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister64.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister65.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister66.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister67.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister68.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister69.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister70.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister71.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister72.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister73.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister74.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister75.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister76.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister77.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister78.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister79.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister80.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister81.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister82.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister83.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister84.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister85.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister86.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister87.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister88.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister89.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister90.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister91.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister92.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister93.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister94.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister95.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister96.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister97.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister98.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister99.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister100.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister101.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister102.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister103.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister104.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister105.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister106.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister107.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister108.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister109.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister110.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister112.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister113.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister114.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister115.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister116.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister117.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister118.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister119.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister120.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister121.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister122.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister123.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister124.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister125.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister126.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister127.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister128.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister129.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister130.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister131.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister132.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister133.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister134.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister135.jpg') },
            { image: require('./../../assets/photos/kochmeister/kochmeister136.jpg') },
        ]
        })

    }

</script>



<style>

     @import './../../assets/styles/galerie.css';

</style>
