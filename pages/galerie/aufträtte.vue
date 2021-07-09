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
            { image: require('./../../assets/photos/aufträtte/aufträtte1.jpg') },
            { image: require('./../../assets/photos/aufträtte/aufträtte2.jpg') },
            { image: require('./../../assets/photos/aufträtte/aufträtte3.jpg') },
            { image: require('./../../assets/photos/aufträtte/aufträtte4.jpg') },
            { image: require('./../../assets/photos/aufträtte/aufträtte5.jpg') },
            { image: require('./../../assets/photos/aufträtte/aufträtte6.jpg') },
            { image: require('./../../assets/photos/aufträtte/aufträtte7.jpg') },
            { image: require('./../../assets/photos/aufträtte/aufträtte8.jpg') },
            { image: require('./../../assets/photos/aufträtte/aufträtte9.jpg') },
            { image: require('./../../assets/photos/aufträtte/aufträtte10.jpg') },
            { image: require('./../../assets/photos/aufträtte/aufträtte11.jpg') },
            { image: require('./../../assets/photos/aufträtte/aufträtte12.jpg') },
            { image: require('./../../assets/photos/aufträtte/aufträtte13.jpg') },
            { image: require('./../../assets/photos/aufträtte/aufträtte14.jpg') },
            { image: require('./../../assets/photos/aufträtte/aufträtte15.jpg') },
            { image: require('./../../assets/photos/aufträtte/aufträtte16.jpg') },
            { image: require('./../../assets/photos/aufträtte/aufträtte17.jpg') },
            { image: require('./../../assets/photos/aufträtte/aufträtte18.jpg') },
            { image: require('./../../assets/photos/aufträtte/aufträtte19.jpg') },
            { image: require('./../../assets/photos/aufträtte/aufträtte20.jpg') },
            { image: require('./../../assets/photos/aufträtte/aufträtte21.jpg') },
            { image: require('./../../assets/photos/aufträtte/aufträtte22.png') },
            { image: require('./../../assets/photos/aufträtte/aufträtte23.jpg') },
            { image: require('./../../assets/photos/aufträtte/aufträtte24.png') },
            { image: require('./../../assets/photos/aufträtte/aufträtte25.jpg') },
            { image: require('./../../assets/photos/aufträtte/aufträtte26.jpg') },
            { image: require('./../../assets/photos/aufträtte/aufträtte27.jpg') },
            { image: require('./../../assets/photos/aufträtte/aufträtte28.png') },
            { image: require('./../../assets/photos/aufträtte/aufträtte29.jpg') },
            { image: require('./../../assets/photos/aufträtte/aufträtte30.png') },
            { image: require('./../../assets/photos/aufträtte/aufträtte31.png') },
            { image: require('./../../assets/photos/aufträtte/aufträtte32.png') },
            { image: require('./../../assets/photos/aufträtte/aufträtte33.png') },
            { image: require('./../../assets/photos/aufträtte/aufträtte34.png') },
            { image: require('./../../assets/photos/aufträtte/aufträtte35.png') },
            { image: require('./../../assets/photos/aufträtte/aufträtte36.png') },
            { image: require('./../../assets/photos/aufträtte/aufträtte37.png') },
            { image: require('./../../assets/photos/aufträtte/aufträtte38.png') },
            { image: require('./../../assets/photos/aufträtte/aufträtte39.png') },
            { image: require('./../../assets/photos/aufträtte/aufträtte40.png') },
            { image: require('./../../assets/photos/aufträtte/aufträtte41.png') },
            { image: require('./../../assets/photos/aufträtte/aufträtte42.png') },
            { image: require('./../../assets/photos/aufträtte/aufträtte43.png') },
            { image: require('./../../assets/photos/aufträtte/aufträtte44.png') },
            { image: require('./../../assets/photos/aufträtte/aufträtte45.png') },
            { image: require('./../../assets/photos/aufträtte/aufträtte46.png') },
            { image: require('./../../assets/photos/aufträtte/aufträtte47.png') },
            { image: require('./../../assets/photos/aufträtte/aufträtte48.png') },
            { image: require('./../../assets/photos/aufträtte/aufträtte49.png') },
            { image: require('./../../assets/photos/aufträtte/aufträtte50.png') },
            { image: require('./../../assets/photos/aufträtte/aufträtte51.png') },
            { image: require('./../../assets/photos/aufträtte/aufträtte52.png') },
            { image: require('./../../assets/photos/aufträtte/aufträtte53.png') },
            { image: require('./../../assets/photos/aufträtte/aufträtte54.png') },
            { image: require('./../../assets/photos/aufträtte/aufträtte55.png') },
            { image: require('./../../assets/photos/aufträtte/aufträtte56.png') },
            { image: require('./../../assets/photos/aufträtte/aufträtte57.png') },
            { image: require('./../../assets/photos/aufträtte/aufträtte58.png') },
            { image: require('./../../assets/photos/aufträtte/aufträtte59.png') },
            { image: require('./../../assets/photos/aufträtte/aufträtte60.png') },
            { image: require('./../../assets/photos/aufträtte/aufträtte61.png') },
            { image: require('./../../assets/photos/aufträtte/aufträtte62.png') },
            { image: require('./../../assets/photos/aufträtte/aufträtte63.png') },
            { image: require('./../../assets/photos/aufträtte/aufträtte64.png') },
            { image: require('./../../assets/photos/aufträtte/aufträtte65.jpg') },
            { image: require('./../../assets/photos/aufträtte/aufträtte66.jpg') },
            { image: require('./../../assets/photos/aufträtte/aufträtte67.jpg') },
            { image: require('./../../assets/photos/aufträtte/aufträtte68.jpg') },
            { image: require('./../../assets/photos/aufträtte/aufträtte69.jpg') },
            { image: require('./../../assets/photos/aufträtte/aufträtte70.jpg') },
            { image: require('./../../assets/photos/aufträtte/aufträtte71.jpg') },
            { image: require('./../../assets/photos/aufträtte/aufträtte72.jpg') },
            { image: require('./../../assets/photos/aufträtte/aufträtte73.jpg') },
            { image: require('./../../assets/photos/aufträtte/aufträtte74.jpg') },
            { image: require('./../../assets/photos/aufträtte/aufträtte75.jpg') },
            { image: require('./../../assets/photos/aufträtte/aufträtte76.jpg') },
        ]
        })

    }

</script>



<style>

     @import './../../assets/styles/galerie.css';

</style>
