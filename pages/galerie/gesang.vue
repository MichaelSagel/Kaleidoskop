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
            require('./../../assets/photos/gesang/gesang16.jpg') ,
            require('./../../assets/photos/gesang/gesang17.jpg') ,
            require('./../../assets/photos/gesang/gesang18.jpg') ,
            require('./../../assets/photos/gesang/gesang19.jpg') ,
            require('./../../assets/photos/gesang/gesang20.jpg') ,
            require('./../../assets/photos/gesang/gesang21.jpg') ,
            require('./../../assets/photos/gesang/gesang22.jpg') ,
            require('./../../assets/photos/gesang/gesang23.jpg') ,
            require('./../../assets/photos/gesang/gesang24.jpg') ,
            require('./../../assets/photos/gesang/gesang25.jpg') ,
            require('./../../assets/photos/gesang/gesang26.jpg') ,
            require('./../../assets/photos/gesang/gesang27.jpg') ,
            require('./../../assets/photos/gesang/gesang28.jpg') ,
            require('./../../assets/photos/gesang/gesang29.jpg') ,
            require('./../../assets/photos/gesang/gesang30.jpg') ,
            require('./../../assets/photos/gesang/gesang31.jpg') ,
            require('./../../assets/photos/gesang/gesang32.jpg') ,
            require('./../../assets/photos/gesang/gesang33.jpg') ,
            require('./../../assets/photos/gesang/gesang34.jpg') ,
            require('./../../assets/photos/gesang/gesang35.jpg') ,
            require('./../../assets/photos/gesang/gesang36.jpg') ,
            require('./../../assets/photos/gesang/gesang37.jpg') ,
            require('./../../assets/photos/gesang/gesang38.jpg') ,
            require('./../../assets/photos/gesang/gesang39.jpg') ,
            require('./../../assets/photos/gesang/gesang40.jpg') ,
            require('./../../assets/photos/gesang/gesang41.jpg') ,
            require('./../../assets/photos/gesang/gesang42.jpg') ,
            require('./../../assets/photos/gesang/gesang43.jpg') ,
            require('./../../assets/photos/gesang/gesang44.jpg') ,
            require('./../../assets/photos/gesang/gesang45.jpg') ,
            require('./../../assets/photos/gesang/gesang46.jpg') ,
            require('./../../assets/photos/gesang/gesang47.jpg') ,
            require('./../../assets/photos/gesang/gesang48.jpg') ,
            require('./../../assets/photos/gesang/gesang49.jpg') ,
            require('./../../assets/photos/gesang/gesang50.jpg') ,
            require('./../../assets/photos/gesang/gesang51.jpg') ,
            require('./../../assets/photos/gesang/gesang52.jpg') ,
            require('./../../assets/photos/gesang/gesang53.jpg') ,
            require('./../../assets/photos/gesang/gesang54.jpg') ,
            require('./../../assets/photos/gesang/gesang55.jpg') ,
            require('./../../assets/photos/gesang/gesang56.jpg') ,
            require('./../../assets/photos/gesang/gesang57.jpg') ,
            require('./../../assets/photos/gesang/gesang58.jpg') ,
            require('./../../assets/photos/gesang/gesang59.jpg') ,
            require('./../../assets/photos/gesang/gesang60.jpg') ,
            require('./../../assets/photos/gesang/gesang61.jpg') ,
            require('./../../assets/photos/gesang/gesang62.jpg') ,
            require('./../../assets/photos/gesang/gesang63.jpg') ,
            require('./../../assets/photos/gesang/gesang64.jpg') ,
            require('./../../assets/photos/gesang/gesang65.jpg') ,
            require('./../../assets/photos/gesang/gesang66.jpg') ,
            require('./../../assets/photos/gesang/gesang67.jpg') ,
            require('./../../assets/photos/gesang/gesang68.jpg') ,
            require('./../../assets/photos/gesang/gesang69.jpg') ,
            require('./../../assets/photos/gesang/gesang70.jpg') ,
            require('./../../assets/photos/gesang/gesang71.jpg') ,
            require('./../../assets/photos/gesang/gesang72.jpg') ,
            require('./../../assets/photos/gesang/gesang73.jpg') ,
            require('./../../assets/photos/gesang/gesang74.jpg') ,
            require('./../../assets/photos/gesang/gesang75.jpg') ,
            require('./../../assets/photos/gesang/gesang76.jpg') ,
            require('./../../assets/photos/gesang/gesang77.jpg') ,
            require('./../../assets/photos/gesang/gesang78.jpg') ,
            require('./../../assets/photos/gesang/gesang79.jpg') ,
            require('./../../assets/photos/gesang/gesang80.jpg') ,
            require('./../../assets/photos/gesang/gesang81.jpg') ,
            require('./../../assets/photos/gesang/gesang82.jpg') ,
            require('./../../assets/photos/gesang/gesang83.jpg') ,
            require('./../../assets/photos/gesang/gesang84.jpg') ,
            require('./../../assets/photos/gesang/gesang85.jpg') ,
            require('./../../assets/photos/gesang/gesang86.jpg') ,
            require('./../../assets/photos/gesang/gesang87.jpg') ,
            require('./../../assets/photos/gesang/gesang88.jpg') ,
        ],
    index: null
        })

    }

</script>



<style>

     @import './../../assets/styles/galerie.css';

</style>