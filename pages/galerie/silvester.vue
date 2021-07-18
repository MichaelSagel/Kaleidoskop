<template>

    <div class="galerieContainer">

        <div id="app" class="photoContainer">
            <img class="image" v-for="(image, i) in images" :src="image" :key="i" @click="index = i">
            <client-only placeholder="Loading...">
                <VueGallerySlideshow :images="images" :index="index" @close="index = null" />
            </client-only>
        </div>

    </div>

</template>


<script>

    import VueGallerySlideshow from 'vue-gallery-slideshow';

    export default {
    components: { VueGallerySlideshow },
  
    data: () => ({
        images: [
            require('./../../assets/photos/silvester/silvester1.jpg') ,
            require('./../../assets/photos/silvester/silvester2.jpg') ,
            require('./../../assets/photos/silvester/silvester3.jpg') ,
            require('./../../assets/photos/silvester/silvester4.jpg') ,
            require('./../../assets/photos/silvester/silvester5.jpg') ,
            require('./../../assets/photos/silvester/silvester6.jpg') ,
            require('./../../assets/photos/silvester/silvester7.jpg') ,
            require('./../../assets/photos/silvester/silvester8.jpg') ,
            require('./../../assets/photos/silvester/silvester9.jpg') ,
            require('./../../assets/photos/silvester/silvester10.jpg') ,
            require('./../../assets/photos/silvester/silvester11.jpg') ,
            require('./../../assets/photos/silvester/silvester12.jpg') ,
            require('./../../assets/photos/silvester/silvester13.jpg') ,
            require('./../../assets/photos/silvester/silvester14.jpg') ,
            require('./../../assets/photos/silvester/silvester15.jpg') ,
            require('./../../assets/photos/silvester/silvester16.jpg') ,
            require('./../../assets/photos/silvester/silvester17.jpg') ,
            require('./../../assets/photos/silvester/silvester18.jpg') ,
            require('./../../assets/photos/silvester/silvester19.jpg') ,
            require('./../../assets/photos/silvester/silvester20.jpg') ,
            require('./../../assets/photos/silvester/silvester21.jpg') ,
            require('./../../assets/photos/silvester/silvester22.jpg') ,
            require('./../../assets/photos/silvester/silvester23.jpg') ,
            require('./../../assets/photos/silvester/silvester24.jpg') ,
            require('./../../assets/photos/silvester/silvester25.jpg') ,
            require('./../../assets/photos/silvester/silvester26.jpg') ,
            require('./../../assets/photos/silvester/silvester27.jpg') ,
            require('./../../assets/photos/silvester/silvester28.jpg') ,
            require('./../../assets/photos/silvester/silvester29.jpg') ,
            require('./../../assets/photos/silvester/silvester30.jpg') ,
            require('./../../assets/photos/silvester/silvester31.jpg') ,
            require('./../../assets/photos/silvester/silvester32.jpg') ,
            require('./../../assets/photos/silvester/silvester33.jpg') ,
            require('./../../assets/photos/silvester/silvester34.jpg') ,
            require('./../../assets/photos/silvester/silvester35.jpg') ,
            require('./../../assets/photos/silvester/silvester36.jpg') ,
            require('./../../assets/photos/silvester/silvester37.jpg') ,
            require('./../../assets/photos/silvester/silvester38.jpg') ,
            require('./../../assets/photos/silvester/silvester39.jpg') ,
            require('./../../assets/photos/silvester/silvester40.jpg') ,
            require('./../../assets/photos/silvester/silvester41.jpg') ,
            require('./../../assets/photos/silvester/silvester42.jpg') ,
            require('./../../assets/photos/silvester/silvester43.jpg') ,
            require('./../../assets/photos/silvester/silvester44.jpg') ,
            require('./../../assets/photos/silvester/silvester45.jpg') ,
            require('./../../assets/photos/silvester/silvester46.jpg') ,
            require('./../../assets/photos/silvester/silvester47.jpg') ,
            require('./../../assets/photos/silvester/silvester48.jpg') ,
            require('./../../assets/photos/silvester/silvester49.jpg') ,
            require('./../../assets/photos/silvester/silvester51.jpg') ,
            require('./../../assets/photos/silvester/silvester52.jpg') ,
            require('./../../assets/photos/silvester/silvester53.jpg') ,
            require('./../../assets/photos/silvester/silvester54.jpg') ,
            require('./../../assets/photos/silvester/silvester55.jpg') ,
            require('./../../assets/photos/silvester/silvester56.jpg') ,
            require('./../../assets/photos/silvester/silvester57.jpg') ,
            require('./../../assets/photos/silvester/silvester58.jpg') ,
            require('./../../assets/photos/silvester/silvester59.jpg') ,
            require('./../../assets/photos/silvester/silvester60.jpg') ,
            require('./../../assets/photos/silvester/silvester61.jpg') ,
            require('./../../assets/photos/silvester/silvester62.jpg') ,
            require('./../../assets/photos/silvester/silvester63.jpg') ,
            require('./../../assets/photos/silvester/silvester64.jpg') ,
            require('./../../assets/photos/silvester/silvester65.jpg') ,
            require('./../../assets/photos/silvester/silvester66.jpg') ,
            require('./../../assets/photos/silvester/silvester67.jpg') ,
            require('./../../assets/photos/silvester/silvester68.jpg') ,
            require('./../../assets/photos/silvester/silvester69.jpg') ,
            require('./../../assets/photos/silvester/silvester70.jpg') ,
            require('./../../assets/photos/silvester/silvester71.jpg') ,
            require('./../../assets/photos/silvester/silvester72.jpg') ,
            require('./../../assets/photos/silvester/silvester73.jpg') ,
            require('./../../assets/photos/silvester/silvester74.jpg') ,
            require('./../../assets/photos/silvester/silvester75.jpg') ,
            require('./../../assets/photos/silvester/silvester76.jpg') ,
            require('./../../assets/photos/silvester/silvester77.jpg') ,
            require('./../../assets/photos/silvester/silvester78.jpg') ,
            require('./../../assets/photos/silvester/silvester79.jpg') ,
            require('./../../assets/photos/silvester/silvester80.jpg') ,
            require('./../../assets/photos/silvester/silvester81.jpg') ,
            require('./../../assets/photos/silvester/silvester82.jpg') ,
            require('./../../assets/photos/silvester/silvester83.jpg') ,
            require('./../../assets/photos/silvester/silvester84.jpg') ,
            require('./../../assets/photos/silvester/silvester85.jpg') ,
            require('./../../assets/photos/silvester/silvester86.jpg') ,
            require('./../../assets/photos/silvester/silvester87.jpg') ,
            require('./../../assets/photos/silvester/silvester88.jpg') ,
            require('./../../assets/photos/silvester/silvester89.jpg') ,
            require('./../../assets/photos/silvester/silvester91.jpg') ,
            require('./../../assets/photos/silvester/silvester92.jpg') ,
            require('./../../assets/photos/silvester/silvester93.jpg') ,
            require('./../../assets/photos/silvester/silvester94.jpg') ,
            require('./../../assets/photos/silvester/silvester95.jpg') ,
            require('./../../assets/photos/silvester/silvester96.jpg') ,
            require('./../../assets/photos/silvester/silvester97.jpg') ,
            require('./../../assets/photos/silvester/silvester98.jpg') ,
            require('./../../assets/photos/silvester/silvester99.jpg') ,
            require('./../../assets/photos/silvester/silvester100.jpg') ,
            require('./../../assets/photos/silvester/silvester101.jpg') ,
            require('./../../assets/photos/silvester/silvester102.jpg') ,
            require('./../../assets/photos/silvester/silvester103.jpg') ,
            require('./../../assets/photos/silvester/silvester104.jpg') ,
            require('./../../assets/photos/silvester/silvester105.jpg') ,
            require('./../../assets/photos/silvester/silvester106.jpg') ,
            require('./../../assets/photos/silvester/silvester107.jpg') ,
            require('./../../assets/photos/silvester/silvester108.jpg') ,
            require('./../../assets/photos/silvester/silvester109.jpg') ,
            require('./../../assets/photos/silvester/silvester110.jpg') ,
            require('./../../assets/photos/silvester/silvester111.jpg') ,
            require('./../../assets/photos/silvester/silvester112.jpg') ,
            require('./../../assets/photos/silvester/silvester113.jpg') ,
            require('./../../assets/photos/silvester/silvester114.jpg') ,
            require('./../../assets/photos/silvester/silvester115.jpg') ,
            require('./../../assets/photos/silvester/silvester116.jpg') ,
            require('./../../assets/photos/silvester/silvester117.jpg') ,
            require('./../../assets/photos/silvester/silvester118.jpg') ,
            require('./../../assets/photos/silvester/silvester119.jpg') ,
            require('./../../assets/photos/silvester/silvester120.jpg') ,
            require('./../../assets/photos/silvester/silvester121.jpg') ,
            require('./../../assets/photos/silvester/silvester122.jpg') ,
            require('./../../assets/photos/silvester/silvester123.jpg') ,
            require('./../../assets/photos/silvester/silvester124.jpg') ,
            require('./../../assets/photos/silvester/silvester125.jpg') ,
            require('./../../assets/photos/silvester/silvester126.jpg') ,
            require('./../../assets/photos/silvester/silvester127.jpg') ,
            require('./../../assets/photos/silvester/silvester128.jpg') ,
            require('./../../assets/photos/silvester/silvester129.jpg') ,
            require('./../../assets/photos/silvester/silvester130.jpg') ,
            require('./../../assets/photos/silvester/silvester131.jpg') ,
            require('./../../assets/photos/silvester/silvester132.jpg') ,
            require('./../../assets/photos/silvester/silvester133.jpg') ,
            require('./../../assets/photos/silvester/silvester134.jpg') ,
            require('./../../assets/photos/silvester/silvester135.jpg') ,
            require('./../../assets/photos/silvester/silvester136.jpg') ,
            require('./../../assets/photos/silvester/silvester137.jpg') ,
            require('./../../assets/photos/silvester/silvester138.jpg') ,
            require('./../../assets/photos/silvester/silvester139.jpg') ,
            require('./../../assets/photos/silvester/silvester140.jpg') ,
            require('./../../assets/photos/silvester/silvester141.jpg') ,
        ],
    index: null
        })

    }

</script>



<style>

     @import './../../assets/styles/galerie.css';

</style>