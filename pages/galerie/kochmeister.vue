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
            require('./../../assets/photos/kochmeister/kochmeister1.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister2.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister3.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister4.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister5.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister6.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister7.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister8.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister9.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister10.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister11.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister12.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister13.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister14.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister15.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister16.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister17.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister18.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister19.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister20.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister21.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister22.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister23.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister24.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister25.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister26.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister27.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister28.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister29.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister30.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister31.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister32.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister33.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister34.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister35.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister36.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister37.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister38.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister39.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister40.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister41.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister42.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister43.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister44.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister45.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister46.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister47.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister48.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister49.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister50.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister51.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister52.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister53.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister54.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister55.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister56.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister57.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister58.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister59.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister60.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister61.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister62.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister63.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister64.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister65.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister66.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister67.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister68.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister69.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister70.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister71.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister72.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister73.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister74.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister75.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister76.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister77.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister78.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister79.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister80.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister81.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister82.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister83.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister84.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister85.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister86.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister87.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister88.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister89.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister90.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister91.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister92.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister93.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister94.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister95.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister96.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister97.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister98.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister99.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister100.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister101.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister102.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister103.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister104.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister105.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister106.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister107.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister108.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister109.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister110.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister112.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister113.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister114.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister115.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister116.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister117.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister118.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister119.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister120.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister121.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister122.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister123.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister124.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister125.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister126.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister127.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister128.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister129.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister130.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister131.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister132.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister133.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister134.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister135.jpg') ,
            require('./../../assets/photos/kochmeister/kochmeister136.jpg') ,
        ],
    index: null
        })

    }

</script>



<style>

     @import './../../assets/styles/galerie.css';

</style>