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
            { image: require('./../../assets/photos/camps/camps1.jpg') },
            { image: require('./../../assets/photos/camps/camps2.jpg') },
            { image: require('./../../assets/photos/camps/camps3.jpg') },
            { image: require('./../../assets/photos/camps/camps4.jpg') },
            { image: require('./../../assets/photos/camps/camps5.jpg') },
            { image: require('./../../assets/photos/camps/camps6.jpg') },
            { image: require('./../../assets/photos/camps/camps7.jpg') },
            { image: require('./../../assets/photos/camps/camps8.jpg') },
            { image: require('./../../assets/photos/camps/camps9.png') },
            { image: require('./../../assets/photos/camps/camps10.png') },
            { image: require('./../../assets/photos/camps/camps11.png') },
            { image: require('./../../assets/photos/camps/camps12.png') },
            { image: require('./../../assets/photos/camps/camps13.jpg') },
            { image: require('./../../assets/photos/camps/camps14.png') },
            { image: require('./../../assets/photos/camps/camps15.jpg') },
            { image: require('./../../assets/photos/camps/camps16.png') },
            { image: require('./../../assets/photos/camps/camps17.jpg') },
            { image: require('./../../assets/photos/camps/camps18.jpg') },
            { image: require('./../../assets/photos/camps/camps19.png') },
            { image: require('./../../assets/photos/camps/camps20.png') },
            { image: require('./../../assets/photos/camps/camps21.png') },
            { image: require('./../../assets/photos/camps/camps22.png') },
            { image: require('./../../assets/photos/camps/camps23.png') },
            { image: require('./../../assets/photos/camps/camps24.png') },
            { image: require('./../../assets/photos/camps/camps25.png') },
            { image: require('./../../assets/photos/camps/camps26.png') },
            { image: require('./../../assets/photos/camps/camps27.png') },
            { image: require('./../../assets/photos/camps/camps28.png') },
            { image: require('./../../assets/photos/camps/camps29.png') },
            { image: require('./../../assets/photos/camps/camps30.png') },
            { image: require('./../../assets/photos/camps/camps31.png') },
            { image: require('./../../assets/photos/camps/camps32.png') },
            { image: require('./../../assets/photos/camps/camps33.png') },
            { image: require('./../../assets/photos/camps/camps34.png') },
            { image: require('./../../assets/photos/camps/camps35.png') },
            { image: require('./../../assets/photos/camps/camps36.png') },
            { image: require('./../../assets/photos/camps/camps37.png') },
            { image: require('./../../assets/photos/camps/camps38.png') },
            { image: require('./../../assets/photos/camps/camps39.png') },
            { image: require('./../../assets/photos/camps/camps40.png') },
            { image: require('./../../assets/photos/camps/camps41.png') },
            { image: require('./../../assets/photos/camps/camps42.jpg') },
            { image: require('./../../assets/photos/camps/camps43.jpg') },
            { image: require('./../../assets/photos/camps/camps44.jpg') },
            { image: require('./../../assets/photos/camps/camps45.jpg') },
            { image: require('./../../assets/photos/camps/camps46.jpg') },
            { image: require('./../../assets/photos/camps/camps47.jpg') },
            { image: require('./../../assets/photos/camps/camps48.jpg') },
            { image: require('./../../assets/photos/camps/camps49.jpg') },
            { image: require('./../../assets/photos/camps/camps50.jpg') },
            { image: require('./../../assets/photos/camps/camps51.jpg') },
            { image: require('./../../assets/photos/camps/camps52.jpg') },
            { image: require('./../../assets/photos/camps/camps53.jpg') },
            { image: require('./../../assets/photos/camps/camps54.jpg') },
            { image: require('./../../assets/photos/camps/camps55.jpg') },
            { image: require('./../../assets/photos/camps/camps56.jpg') },
            { image: require('./../../assets/photos/camps/camps57.jpg') },
            { image: require('./../../assets/photos/camps/camps58.jpg') },
            { image: require('./../../assets/photos/camps/camps59.jpg') },
            { image: require('./../../assets/photos/camps/camps60.jpg') },
            { image: require('./../../assets/photos/camps/camps61.jpg') },
            { image: require('./../../assets/photos/camps/camps62.jpg') },
            { image: require('./../../assets/photos/camps/camps63.jpg') },
            { image: require('./../../assets/photos/camps/camps64.jpg') },
            { image: require('./../../assets/photos/camps/camps65.jpg') },
            { image: require('./../../assets/photos/camps/camps66.jpg') },
            { image: require('./../../assets/photos/camps/camps67.jpg') },
            { image: require('./../../assets/photos/camps/camps68.jpg') },
            { image: require('./../../assets/photos/camps/camps69.jpg') },
            { image: require('./../../assets/photos/camps/camps70.jpg') },
            { image: require('./../../assets/photos/camps/camps71.jpg') },
            { image: require('./../../assets/photos/camps/camps72.jpg') },
            { image: require('./../../assets/photos/camps/camps73.jpg') },
            { image: require('./../../assets/photos/camps/camps74.jpg') },
            { image: require('./../../assets/photos/camps/camps75.jpg') },
        ]
        })

    }

</script>



<style>

     @import './../../assets/styles/galerie.css';

</style>
