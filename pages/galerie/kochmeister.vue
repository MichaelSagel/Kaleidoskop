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
        ],
    index: null
        })

    }

</script>



<style>

     @import './../../assets/styles/galerie.css';

</style>