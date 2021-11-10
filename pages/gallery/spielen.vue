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
            require('./../../assets/photos/spielen/spielen1.jpg') ,
            require('./../../assets/photos/spielen/spielen2.jpg') ,
            require('./../../assets/photos/spielen/spielen3.jpg') ,
            require('./../../assets/photos/spielen/spielen4.jpg') ,
            require('./../../assets/photos/spielen/spielen5.jpg') ,
            require('./../../assets/photos/spielen/spielen6.jpg') ,
            require('./../../assets/photos/spielen/spielen7.jpg') ,
            require('./../../assets/photos/spielen/spielen8.jpg') ,
            require('./../../assets/photos/spielen/spielen9.jpg') ,
            require('./../../assets/photos/spielen/spielen10.jpg') ,
            require('./../../assets/photos/spielen/spielen11.jpg') ,
            require('./../../assets/photos/spielen/spielen12.jpg') ,
            require('./../../assets/photos/spielen/spielen13.jpg') ,
            require('./../../assets/photos/spielen/spielen14.jpg') ,
            require('./../../assets/photos/spielen/spielen15.jpg') ,
            require('./../../assets/photos/spielen/spielen16.jpg') ,
            require('./../../assets/photos/spielen/spielen17.jpg') ,
            require('./../../assets/photos/spielen/spielen18.jpg') ,
        ],
    index: null
        })

    }

</script>



<style>

     @import './../../assets/styles/gallery.css';

</style>