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
            { image: require('./../../assets/photos/gesang/gesang1.jpg') },
            { image: require('./../../assets/photos/gesang/gesang2.jpg') },
            { image: require('./../../assets/photos/gesang/gesang3.jpg') },
            { image: require('./../../assets/photos/gesang/gesang4.jpg') },
            { image: require('./../../assets/photos/gesang/gesang5.jpg') },
            { image: require('./../../assets/photos/gesang/gesang6.jpg') },
            { image: require('./../../assets/photos/gesang/gesang7.jpg') },
            { image: require('./../../assets/photos/gesang/gesang8.jpg') },
            { image: require('./../../assets/photos/gesang/gesang9.jpg') },
            { image: require('./../../assets/photos/gesang/gesang10.jpg') },
            { image: require('./../../assets/photos/gesang/gesang11.jpg') },
            { image: require('./../../assets/photos/gesang/gesang12.jpg') },
            { image: require('./../../assets/photos/gesang/gesang13.jpg') },
            { image: require('./../../assets/photos/gesang/gesang14.jpg') },
            { image: require('./../../assets/photos/gesang/gesang15.jpg') },
            { image: require('./../../assets/photos/gesang/gesang16.jpg') },
            { image: require('./../../assets/photos/gesang/gesang17.jpg') },
            { image: require('./../../assets/photos/gesang/gesang18.jpg') },
            { image: require('./../../assets/photos/gesang/gesang19.jpg') },
            { image: require('./../../assets/photos/gesang/gesang20.jpg') },
            { image: require('./../../assets/photos/gesang/gesang21.jpg') },
            { image: require('./../../assets/photos/gesang/gesang22.jpg') },
            { image: require('./../../assets/photos/gesang/gesang23.jpg') },
            { image: require('./../../assets/photos/gesang/gesang24.jpg') },
            { image: require('./../../assets/photos/gesang/gesang25.jpg') },
            { image: require('./../../assets/photos/gesang/gesang26.jpg') },
            { image: require('./../../assets/photos/gesang/gesang27.jpg') },
            { image: require('./../../assets/photos/gesang/gesang28.jpg') },
            { image: require('./../../assets/photos/gesang/gesang29.jpg') },
            { image: require('./../../assets/photos/gesang/gesang30.jpg') },
            { image: require('./../../assets/photos/gesang/gesang31.jpg') },
            { image: require('./../../assets/photos/gesang/gesang32.jpg') },
            { image: require('./../../assets/photos/gesang/gesang33.jpg') },
            { image: require('./../../assets/photos/gesang/gesang34.jpg') },
            { image: require('./../../assets/photos/gesang/gesang35.jpg') },
            { image: require('./../../assets/photos/gesang/gesang36.jpg') },
            { image: require('./../../assets/photos/gesang/gesang37.jpg') },
            { image: require('./../../assets/photos/gesang/gesang38.jpg') },
            { image: require('./../../assets/photos/gesang/gesang39.jpg') },
            { image: require('./../../assets/photos/gesang/gesang40.jpg') },
            { image: require('./../../assets/photos/gesang/gesang41.jpg') },
            { image: require('./../../assets/photos/gesang/gesang42.jpg') },
            { image: require('./../../assets/photos/gesang/gesang43.jpg') },
            { image: require('./../../assets/photos/gesang/gesang44.jpg') },
            { image: require('./../../assets/photos/gesang/gesang45.jpg') },
            { image: require('./../../assets/photos/gesang/gesang46.jpg') },
            { image: require('./../../assets/photos/gesang/gesang47.jpg') },
            { image: require('./../../assets/photos/gesang/gesang48.jpg') },
            { image: require('./../../assets/photos/gesang/gesang49.jpg') },
            { image: require('./../../assets/photos/gesang/gesang50.jpg') },
            { image: require('./../../assets/photos/gesang/gesang51.jpg') },
            { image: require('./../../assets/photos/gesang/gesang52.jpg') },
            { image: require('./../../assets/photos/gesang/gesang53.jpg') },
            { image: require('./../../assets/photos/gesang/gesang54.jpg') },
            { image: require('./../../assets/photos/gesang/gesang55.jpg') },
            { image: require('./../../assets/photos/gesang/gesang56.jpg') },
            { image: require('./../../assets/photos/gesang/gesang57.jpg') },
            { image: require('./../../assets/photos/gesang/gesang58.jpg') },
            { image: require('./../../assets/photos/gesang/gesang59.jpg') },
            { image: require('./../../assets/photos/gesang/gesang60.jpg') },
            { image: require('./../../assets/photos/gesang/gesang61.jpg') },
            { image: require('./../../assets/photos/gesang/gesang62.jpg') },
            { image: require('./../../assets/photos/gesang/gesang63.jpg') },
            { image: require('./../../assets/photos/gesang/gesang64.jpg') },
            { image: require('./../../assets/photos/gesang/gesang65.jpg') },
            { image: require('./../../assets/photos/gesang/gesang66.jpg') },
            { image: require('./../../assets/photos/gesang/gesang67.jpg') },
            { image: require('./../../assets/photos/gesang/gesang68.jpg') },
            { image: require('./../../assets/photos/gesang/gesang69.jpg') },
            { image: require('./../../assets/photos/gesang/gesang70.jpg') },
            { image: require('./../../assets/photos/gesang/gesang71.jpg') },
            { image: require('./../../assets/photos/gesang/gesang72.jpg') },
            { image: require('./../../assets/photos/gesang/gesang73.jpg') },
            { image: require('./../../assets/photos/gesang/gesang74.jpg') },
            { image: require('./../../assets/photos/gesang/gesang75.jpg') },
            { image: require('./../../assets/photos/gesang/gesang76.jpg') },
            { image: require('./../../assets/photos/gesang/gesang77.jpg') },
            { image: require('./../../assets/photos/gesang/gesang78.jpg') },
            { image: require('./../../assets/photos/gesang/gesang79.jpg') },
            { image: require('./../../assets/photos/gesang/gesang80.jpg') },
            { image: require('./../../assets/photos/gesang/gesang81.jpg') },
            { image: require('./../../assets/photos/gesang/gesang82.jpg') },
            { image: require('./../../assets/photos/gesang/gesang83.jpg') },
            { image: require('./../../assets/photos/gesang/gesang84.jpg') },
            { image: require('./../../assets/photos/gesang/gesang85.jpg') },
            { image: require('./../../assets/photos/gesang/gesang86.jpg') },
            { image: require('./../../assets/photos/gesang/gesang87.jpg') },
            { image: require('./../../assets/photos/gesang/gesang88.jpg') },
        ]
        })

    }

</script>



<style>

     @import './../../assets/styles/galerie.css';

</style>
