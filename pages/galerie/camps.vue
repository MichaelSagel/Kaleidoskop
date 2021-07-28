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
            require('./../../assets/photos/camps/camps1.jpg') ,
            require('./../../assets/photos/camps/camps2.jpg') ,
            require('./../../assets/photos/camps/camps3.jpg') ,
            require('./../../assets/photos/camps/camps4.jpg') ,
            require('./../../assets/photos/camps/camps5.jpg') ,
            require('./../../assets/photos/camps/camps6.jpg') ,
            require('./../../assets/photos/camps/camps7.jpg') ,
            require('./../../assets/photos/camps/camps8.jpg') ,
            require('./../../assets/photos/camps/camps9.jpg') ,
            require('./../../assets/photos/camps/camps10.jpg') ,
            require('./../../assets/photos/camps/camps11.jpg') ,
            require('./../../assets/photos/camps/camps12.png') ,
            require('./../../assets/photos/camps/camps13.png') ,
            require('./../../assets/photos/camps/camps14.png') ,
            require('./../../assets/photos/camps/camps15.png') ,
            require('./../../assets/photos/camps/camps16.png') ,
            require('./../../assets/photos/camps/camps17.png') ,
            require('./../../assets/photos/camps/camps18.png') ,
            require('./../../assets/photos/camps/camps19.png') ,
            require('./../../assets/photos/camps/camps20.png') ,
            require('./../../assets/photos/camps/camps21.png') ,
        ],
    index: null
        })

    }

</script>



<style>

     @import './../../assets/styles/galerie.css';

</style>
