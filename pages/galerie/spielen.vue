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
            require('./../../assets/photos/spielen/spielen19.jpg') ,
            require('./../../assets/photos/spielen/spielen21.jpg') ,
            require('./../../assets/photos/spielen/spielen22.jpg') ,
            require('./../../assets/photos/spielen/spielen23.jpg') ,
            require('./../../assets/photos/spielen/spielen24.jpg') ,
            require('./../../assets/photos/spielen/spielen25.jpg') ,
            require('./../../assets/photos/spielen/spielen26.jpg') ,
            require('./../../assets/photos/spielen/spielen27.jpg') ,
            require('./../../assets/photos/spielen/spielen28.jpg') ,
            require('./../../assets/photos/spielen/spielen29.jpg') ,
            require('./../../assets/photos/spielen/spielen30.jpg') ,
            require('./../../assets/photos/spielen/spielen31.jpg') ,
            require('./../../assets/photos/spielen/spielen32.jpg') ,
            require('./../../assets/photos/spielen/spielen33.jpg') ,
            require('./../../assets/photos/spielen/spielen34.jpg') ,
            require('./../../assets/photos/spielen/spielen35.jpg') ,
            require('./../../assets/photos/spielen/spielen36.jpg') ,
            require('./../../assets/photos/spielen/spielen37.jpg') ,
            require('./../../assets/photos/spielen/spielen38.jpg') ,
            require('./../../assets/photos/spielen/spielen39.jpg') ,
            require('./../../assets/photos/spielen/spielen40.jpg') ,
            require('./../../assets/photos/spielen/spielen41.jpg') ,
            require('./../../assets/photos/spielen/spielen42.jpg') ,
            require('./../../assets/photos/spielen/spielen43.jpg') ,
            require('./../../assets/photos/spielen/spielen44.jpg') ,
            require('./../../assets/photos/spielen/spielen45.jpg') ,
            require('./../../assets/photos/spielen/spielen46.jpg') ,
        ],
    index: null
        })

    }

</script>



<style>

     @import './../../assets/styles/galerie.css';

</style>