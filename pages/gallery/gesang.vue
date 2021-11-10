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
            require('./../../assets/photos/gesang/gesang1.jpg') ,
            require('./../../assets/photos/gesang/gesang2.jpg') ,
            require('./../../assets/photos/gesang/gesang3.jpg') ,
            require('./../../assets/photos/gesang/gesang4.jpg') ,
            require('./../../assets/photos/gesang/gesang5.jpg') ,
            require('./../../assets/photos/gesang/gesang6.jpg') ,
            require('./../../assets/photos/gesang/gesang7.jpg') ,
            require('./../../assets/photos/gesang/gesang8.jpg') ,
            require('./../../assets/photos/gesang/gesang9.jpg') ,
            require('./../../assets/photos/gesang/gesang10.jpg') ,
            require('./../../assets/photos/gesang/gesang11.jpg') ,
            require('./../../assets/photos/gesang/gesang12.jpg') ,
            require('./../../assets/photos/gesang/gesang13.jpg') ,
            require('./../../assets/photos/gesang/gesang14.jpg') ,
            require('./../../assets/photos/gesang/gesang15.jpg') ,
        ],
    index: null
        })

    }

</script>



<style>

     @import './../../assets/styles/gallery.css';

</style>