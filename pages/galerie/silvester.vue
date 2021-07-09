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
            { image: require('./../../assets/photos/silvester/silvester1.jpg') },
            { image: require('./../../assets/photos/silvester/silvester2.jpg') },
            { image: require('./../../assets/photos/silvester/silvester3.jpg') },
            { image: require('./../../assets/photos/silvester/silvester4.jpg') },
            { image: require('./../../assets/photos/silvester/silvester5.jpg') },
            { image: require('./../../assets/photos/silvester/silvester6.jpg') },
            { image: require('./../../assets/photos/silvester/silvester7.jpg') },
            { image: require('./../../assets/photos/silvester/silvester8.jpg') },
            { image: require('./../../assets/photos/silvester/silvester9.jpg') },
            { image: require('./../../assets/photos/silvester/silvester10.jpg') },
            { image: require('./../../assets/photos/silvester/silvester11.jpg') },
            { image: require('./../../assets/photos/silvester/silvester12.jpg') },
            { image: require('./../../assets/photos/silvester/silvester13.jpg') },
            { image: require('./../../assets/photos/silvester/silvester14.jpg') },
            { image: require('./../../assets/photos/silvester/silvester15.jpg') },
            { image: require('./../../assets/photos/silvester/silvester16.jpg') },
            { image: require('./../../assets/photos/silvester/silvester17.jpg') },
            { image: require('./../../assets/photos/silvester/silvester18.jpg') },
            { image: require('./../../assets/photos/silvester/silvester19.jpg') },
            { image: require('./../../assets/photos/silvester/silvester20.jpg') },
            { image: require('./../../assets/photos/silvester/silvester21.jpg') },
            { image: require('./../../assets/photos/silvester/silvester22.jpg') },
            { image: require('./../../assets/photos/silvester/silvester23.jpg') },
            { image: require('./../../assets/photos/silvester/silvester24.jpg') },
            { image: require('./../../assets/photos/silvester/silvester25.jpg') },
            { image: require('./../../assets/photos/silvester/silvester26.jpg') },
            { image: require('./../../assets/photos/silvester/silvester27.jpg') },
            { image: require('./../../assets/photos/silvester/silvester28.jpg') },
            { image: require('./../../assets/photos/silvester/silvester29.jpg') },
            { image: require('./../../assets/photos/silvester/silvester30.jpg') },
            { image: require('./../../assets/photos/silvester/silvester31.jpg') },
            { image: require('./../../assets/photos/silvester/silvester32.jpg') },
            { image: require('./../../assets/photos/silvester/silvester33.jpg') },
            { image: require('./../../assets/photos/silvester/silvester34.jpg') },
            { image: require('./../../assets/photos/silvester/silvester35.jpg') },
            { image: require('./../../assets/photos/silvester/silvester36.jpg') },
            { image: require('./../../assets/photos/silvester/silvester37.jpg') },
            { image: require('./../../assets/photos/silvester/silvester38.jpg') },
            { image: require('./../../assets/photos/silvester/silvester39.jpg') },
            { image: require('./../../assets/photos/silvester/silvester40.jpg') },
            { image: require('./../../assets/photos/silvester/silvester41.jpg') },
            { image: require('./../../assets/photos/silvester/silvester42.jpg') },
            { image: require('./../../assets/photos/silvester/silvester43.jpg') },
            { image: require('./../../assets/photos/silvester/silvester44.jpg') },
            { image: require('./../../assets/photos/silvester/silvester45.jpg') },
            { image: require('./../../assets/photos/silvester/silvester46.jpg') },
            { image: require('./../../assets/photos/silvester/silvester47.jpg') },
            { image: require('./../../assets/photos/silvester/silvester48.jpg') },
            { image: require('./../../assets/photos/silvester/silvester49.jpg') },
            { image: require('./../../assets/photos/silvester/silvester51.jpg') },
            { image: require('./../../assets/photos/silvester/silvester52.jpg') },
            { image: require('./../../assets/photos/silvester/silvester53.jpg') },
            { image: require('./../../assets/photos/silvester/silvester54.jpg') },
            { image: require('./../../assets/photos/silvester/silvester55.jpg') },
            { image: require('./../../assets/photos/silvester/silvester56.jpg') },
            { image: require('./../../assets/photos/silvester/silvester57.jpg') },
            { image: require('./../../assets/photos/silvester/silvester58.jpg') },
            { image: require('./../../assets/photos/silvester/silvester59.jpg') },
            { image: require('./../../assets/photos/silvester/silvester60.jpg') },
            { image: require('./../../assets/photos/silvester/silvester61.jpg') },
            { image: require('./../../assets/photos/silvester/silvester62.jpg') },
            { image: require('./../../assets/photos/silvester/silvester63.jpg') },
            { image: require('./../../assets/photos/silvester/silvester64.jpg') },
            { image: require('./../../assets/photos/silvester/silvester65.jpg') },
            { image: require('./../../assets/photos/silvester/silvester66.jpg') },
            { image: require('./../../assets/photos/silvester/silvester67.jpg') },
            { image: require('./../../assets/photos/silvester/silvester68.jpg') },
            { image: require('./../../assets/photos/silvester/silvester69.jpg') },
            { image: require('./../../assets/photos/silvester/silvester70.jpg') },
            { image: require('./../../assets/photos/silvester/silvester71.jpg') },
            { image: require('./../../assets/photos/silvester/silvester72.jpg') },
            { image: require('./../../assets/photos/silvester/silvester73.jpg') },
            { image: require('./../../assets/photos/silvester/silvester74.jpg') },
            { image: require('./../../assets/photos/silvester/silvester75.jpg') },
            { image: require('./../../assets/photos/silvester/silvester76.jpg') },
            { image: require('./../../assets/photos/silvester/silvester77.jpg') },
            { image: require('./../../assets/photos/silvester/silvester78.jpg') },
            { image: require('./../../assets/photos/silvester/silvester79.jpg') },
            { image: require('./../../assets/photos/silvester/silvester80.jpg') },
            { image: require('./../../assets/photos/silvester/silvester81.jpg') },
            { image: require('./../../assets/photos/silvester/silvester82.jpg') },
            { image: require('./../../assets/photos/silvester/silvester83.jpg') },
            { image: require('./../../assets/photos/silvester/silvester84.jpg') },
            { image: require('./../../assets/photos/silvester/silvester85.jpg') },
            { image: require('./../../assets/photos/silvester/silvester86.jpg') },
            { image: require('./../../assets/photos/silvester/silvester87.jpg') },
            { image: require('./../../assets/photos/silvester/silvester88.jpg') },
            { image: require('./../../assets/photos/silvester/silvester89.jpg') },
            { image: require('./../../assets/photos/silvester/silvester91.jpg') },
            { image: require('./../../assets/photos/silvester/silvester92.jpg') },
            { image: require('./../../assets/photos/silvester/silvester93.jpg') },
            { image: require('./../../assets/photos/silvester/silvester94.jpg') },
            { image: require('./../../assets/photos/silvester/silvester95.jpg') },
            { image: require('./../../assets/photos/silvester/silvester96.jpg') },
            { image: require('./../../assets/photos/silvester/silvester97.jpg') },
            { image: require('./../../assets/photos/silvester/silvester98.jpg') },
            { image: require('./../../assets/photos/silvester/silvester99.jpg') },
            { image: require('./../../assets/photos/silvester/silvester100.jpg') },
            { image: require('./../../assets/photos/silvester/silvester101.jpg') },
            { image: require('./../../assets/photos/silvester/silvester102.jpg') },
            { image: require('./../../assets/photos/silvester/silvester103.jpg') },
            { image: require('./../../assets/photos/silvester/silvester104.jpg') },
            { image: require('./../../assets/photos/silvester/silvester105.jpg') },
            { image: require('./../../assets/photos/silvester/silvester106.jpg') },
            { image: require('./../../assets/photos/silvester/silvester107.jpg') },
            { image: require('./../../assets/photos/silvester/silvester108.jpg') },
            { image: require('./../../assets/photos/silvester/silvester109.jpg') },
            { image: require('./../../assets/photos/silvester/silvester110.jpg') },
            { image: require('./../../assets/photos/silvester/silvester111.jpg') },
            { image: require('./../../assets/photos/silvester/silvester112.jpg') },
            { image: require('./../../assets/photos/silvester/silvester113.jpg') },
            { image: require('./../../assets/photos/silvester/silvester114.jpg') },
            { image: require('./../../assets/photos/silvester/silvester115.jpg') },
            { image: require('./../../assets/photos/silvester/silvester116.jpg') },
            { image: require('./../../assets/photos/silvester/silvester117.jpg') },
            { image: require('./../../assets/photos/silvester/silvester118.jpg') },
            { image: require('./../../assets/photos/silvester/silvester119.jpg') },
            { image: require('./../../assets/photos/silvester/silvester120.jpg') },
            { image: require('./../../assets/photos/silvester/silvester121.jpg') },
            { image: require('./../../assets/photos/silvester/silvester122.jpg') },
            { image: require('./../../assets/photos/silvester/silvester123.jpg') },
            { image: require('./../../assets/photos/silvester/silvester124.jpg') },
            { image: require('./../../assets/photos/silvester/silvester125.jpg') },
            { image: require('./../../assets/photos/silvester/silvester126.jpg') },
            { image: require('./../../assets/photos/silvester/silvester127.jpg') },
            { image: require('./../../assets/photos/silvester/silvester128.jpg') },
            { image: require('./../../assets/photos/silvester/silvester129.jpg') },
            { image: require('./../../assets/photos/silvester/silvester130.jpg') },
            { image: require('./../../assets/photos/silvester/silvester131.jpg') },
            { image: require('./../../assets/photos/silvester/silvester132.jpg') },
            { image: require('./../../assets/photos/silvester/silvester133.jpg') },
            { image: require('./../../assets/photos/silvester/silvester134.jpg') },
            { image: require('./../../assets/photos/silvester/silvester135.jpg') },
            { image: require('./../../assets/photos/silvester/silvester136.jpg') },
            { image: require('./../../assets/photos/silvester/silvester137.jpg') },
            { image: require('./../../assets/photos/silvester/silvester138.jpg') },
            { image: require('./../../assets/photos/silvester/silvester139.jpg') },
            { image: require('./../../assets/photos/silvester/silvester140.jpg') },
            { image: require('./../../assets/photos/silvester/silvester141.jpg') },
        ]
        })

    }

</script>



<style>

     @import './../../assets/styles/galerie.css';

</style>
