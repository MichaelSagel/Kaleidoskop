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
            require('./../../assets/photos/dance/dance1.png') ,
            require('./../../assets/photos/dance/dance2.jpg') ,
            require('./../../assets/photos/dance/dance3.jpg') ,
            require('./../../assets/photos/dance/dance4.jpg') ,
            require('./../../assets/photos/dance/dance5.jpg') ,
            require('./../../assets/photos/dance/dance6.jpg') ,
            require('./../../assets/photos/dance/dance7.jpg') ,
            require('./../../assets/photos/dance/dance8.jpg') ,
            require('./../../assets/photos/dance/dance9.jpg') ,
        ],
    index: null
        })

    }

</script>



<style>

     @import './../../assets/styles/gallery.css';

</style>
