<template>

     <div class="galleryContainer">

        <div id="app" class="photoContainer">
            <div class="image-wrapper"
                v-for="(image, i) in images"
                :key="i" 
            >
                <img 
                    class="image"
                    :src="image"
                    @click="index = i"
                >
            </div>
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
            require('./../../assets/photos/graffiti/graffiti1.jpg') ,
            require('./../../assets/photos/graffiti/graffiti2.jpg') ,
            require('./../../assets/photos/graffiti/graffiti3.jpg') ,
            require('./../../assets/photos/graffiti/graffiti4.jpg') ,
            require('./../../assets/photos/graffiti/graffiti5.jpg') ,
            require('./../../assets/photos/graffiti/graffiti6.jpg') ,
            require('./../../assets/photos/graffiti/graffiti7.jpg') ,
            require('./../../assets/photos/graffiti/graffiti8.jpg') ,
            require('./../../assets/photos/graffiti/graffiti9.jpg') ,
            require('./../../assets/photos/graffiti/graffiti10.jpg') ,
            require('./../../assets/photos/graffiti/graffiti11.jpg') ,
            require('./../../assets/photos/graffiti/graffiti12.jpg') ,
            require('./../../assets/photos/graffiti/graffiti13.jpg') ,
            require('./../../assets/photos/graffiti/graffiti14.jpg') ,
            require('./../../assets/photos/graffiti/graffiti15.jpg') ,
            require('./../../assets/photos/graffiti/graffiti16.jpg') ,
            require('./../../assets/photos/graffiti/graffiti17.jpg') ,
            require('./../../assets/photos/graffiti/graffiti18.jpg') ,
        ],
    index: null
        })

    }

</script>



<style>

     @import './../../assets/styles/gallery.css';

</style>