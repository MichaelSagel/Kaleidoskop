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
            require('./../../assets/photos/künstler/künstler1.jpg') ,
            require('./../../assets/photos/künstler/künstler2.jpg') ,
            require('./../../assets/photos/künstler/künstler3.jpg') ,
            require('./../../assets/photos/künstler/künstler4.jpg') ,
            require('./../../assets/photos/künstler/künstler5.jpg') ,
            require('./../../assets/photos/künstler/künstler6.jpg') ,
            require('./../../assets/photos/künstler/künstler7.jpg') ,
            require('./../../assets/photos/künstler/künstler8.png') ,
            require('./../../assets/photos/künstler/künstler9.jpg') ,
            require('./../../assets/photos/künstler/künstler10.jpg') ,
            require('./../../assets/photos/künstler/künstler11.jpg') ,
            require('./../../assets/photos/künstler/künstler12.jpg') ,
            require('./../../assets/photos/künstler/künstler13.jpg') ,
            require('./../../assets/photos/künstler/künstler14.jpg') ,
            require('./../../assets/photos/künstler/künstler15.jpg') ,
            require('./../../assets/photos/künstler/künstler17.jpg') ,
            require('./../../assets/photos/künstler/künstler18.jpg') ,
            require('./../../assets/photos/künstler/künstler19.jpg') ,
            require('./../../assets/photos/künstler/künstler20.jpg') ,
            require('./../../assets/photos/künstler/künstler21.jpg') ,
            require('./../../assets/photos/künstler/künstler22.jpg') ,
            require('./../../assets/photos/künstler/künstler23.jpg') ,
            require('./../../assets/photos/künstler/künstler24.jpg') ,
            require('./../../assets/photos/künstler/künstler25.jpg') ,
            require('./../../assets/photos/künstler/künstler26.jpg') ,
            require('./../../assets/photos/künstler/künstler27.jpg') ,
            require('./../../assets/photos/künstler/künstler28.jpg') ,
            require('./../../assets/photos/künstler/künstler29.jpg') ,
        ],
    index: null
        })

    }

</script>



<style>

     @import './../../assets/styles/galerie.css';

</style>