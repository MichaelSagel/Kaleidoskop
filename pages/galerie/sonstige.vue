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
            require('./../../assets/photos/sonstige/sonstige1.jpg') ,
            require('./../../assets/photos/sonstige/sonstige2.jpg') ,
            require('./../../assets/photos/sonstige/sonstige3.jpg') ,
            require('./../../assets/photos/sonstige/sonstige4.jpg') ,
            require('./../../assets/photos/sonstige/sonstige5.jpg') ,
            require('./../../assets/photos/sonstige/sonstige6.jpg') ,
            require('./../../assets/photos/sonstige/sonstige7.jpg') ,
            require('./../../assets/photos/sonstige/sonstige8.jpg') ,
            require('./../../assets/photos/sonstige/sonstige9.jpg') ,
            require('./../../assets/photos/sonstige/sonstige10.jpg') ,
            require('./../../assets/photos/sonstige/sonstige11.jpg') ,
            require('./../../assets/photos/sonstige/sonstige12.jpg') ,
            require('./../../assets/photos/sonstige/sonstige13.png') ,
            require('./../../assets/photos/sonstige/sonstige14.jpg') ,
            require('./../../assets/photos/sonstige/sonstige15.jpg') ,
            require('./../../assets/photos/sonstige/sonstige16.png') ,
            require('./../../assets/photos/sonstige/sonstige17.png') ,
            require('./../../assets/photos/sonstige/sonstige18.png') ,
            require('./../../assets/photos/sonstige/sonstige19.png') ,
            require('./../../assets/photos/sonstige/sonstige20.png') ,
            require('./../../assets/photos/sonstige/sonstige21.png') ,
            require('./../../assets/photos/sonstige/sonstige22.png') ,
            require('./../../assets/photos/sonstige/sonstige23.png') ,
            require('./../../assets/photos/sonstige/sonstige24.png') ,
            require('./../../assets/photos/sonstige/sonstige25.png') ,
            require('./../../assets/photos/sonstige/sonstige26.png') ,
            require('./../../assets/photos/sonstige/sonstige27.jpg') ,
            require('./../../assets/photos/sonstige/sonstige28.jpg') ,
            require('./../../assets/photos/sonstige/sonstige29.jpg') ,
            require('./../../assets/photos/sonstige/sonstige30.jpg') ,
            require('./../../assets/photos/sonstige/sonstige31.jpg') ,
        ],
    index: null
        })

    }

</script>



<style>

     @import './../../assets/styles/galerie.css';

</style>