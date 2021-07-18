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
            require('./../../assets/photos/camps/camps9.png') ,
            require('./../../assets/photos/camps/camps10.png') ,
            require('./../../assets/photos/camps/camps11.png') ,
            require('./../../assets/photos/camps/camps12.png') ,
            require('./../../assets/photos/camps/camps13.jpg') ,
            require('./../../assets/photos/camps/camps14.png') ,
            require('./../../assets/photos/camps/camps15.jpg') ,
            require('./../../assets/photos/camps/camps16.png') ,
            require('./../../assets/photos/camps/camps17.jpg') ,
            require('./../../assets/photos/camps/camps18.jpg') ,
            require('./../../assets/photos/camps/camps19.png') ,
            require('./../../assets/photos/camps/camps20.png') ,
            require('./../../assets/photos/camps/camps21.png') ,
            require('./../../assets/photos/camps/camps22.png') ,
            require('./../../assets/photos/camps/camps23.png') ,
            require('./../../assets/photos/camps/camps24.png') ,
            require('./../../assets/photos/camps/camps25.png') ,
            require('./../../assets/photos/camps/camps26.png') ,
            require('./../../assets/photos/camps/camps27.png') ,
            require('./../../assets/photos/camps/camps28.png') ,
            require('./../../assets/photos/camps/camps29.png') ,
            require('./../../assets/photos/camps/camps30.png') ,
            require('./../../assets/photos/camps/camps31.png') ,
            require('./../../assets/photos/camps/camps32.png') ,
            require('./../../assets/photos/camps/camps33.png') ,
            require('./../../assets/photos/camps/camps34.png') ,
            require('./../../assets/photos/camps/camps35.png') ,
            require('./../../assets/photos/camps/camps36.png') ,
            require('./../../assets/photos/camps/camps37.png') ,
            require('./../../assets/photos/camps/camps38.png') ,
            require('./../../assets/photos/camps/camps39.png') ,
            require('./../../assets/photos/camps/camps40.png') ,
            require('./../../assets/photos/camps/camps41.png') ,
            require('./../../assets/photos/camps/camps42.jpg') ,
            require('./../../assets/photos/camps/camps43.jpg') ,
            require('./../../assets/photos/camps/camps44.jpg') ,
            require('./../../assets/photos/camps/camps45.jpg') ,
            require('./../../assets/photos/camps/camps46.jpg') ,
            require('./../../assets/photos/camps/camps47.jpg') ,
            require('./../../assets/photos/camps/camps48.jpg') ,
            require('./../../assets/photos/camps/camps49.jpg') ,
            require('./../../assets/photos/camps/camps50.jpg') ,
            require('./../../assets/photos/camps/camps51.jpg') ,
            require('./../../assets/photos/camps/camps52.jpg') ,
            require('./../../assets/photos/camps/camps53.jpg') ,
            require('./../../assets/photos/camps/camps54.jpg') ,
            require('./../../assets/photos/camps/camps55.jpg') ,
            require('./../../assets/photos/camps/camps56.jpg') ,
            require('./../../assets/photos/camps/camps57.jpg') ,
            require('./../../assets/photos/camps/camps58.jpg') ,
            require('./../../assets/photos/camps/camps59.jpg') ,
            require('./../../assets/photos/camps/camps60.jpg') ,
            require('./../../assets/photos/camps/camps61.jpg') ,
            require('./../../assets/photos/camps/camps62.jpg') ,
            require('./../../assets/photos/camps/camps63.jpg') ,
            require('./../../assets/photos/camps/camps64.jpg') ,
            require('./../../assets/photos/camps/camps65.jpg') ,
            require('./../../assets/photos/camps/camps66.jpg') ,
            require('./../../assets/photos/camps/camps67.jpg') ,
            require('./../../assets/photos/camps/camps68.jpg') ,
            require('./../../assets/photos/camps/camps69.jpg') ,
            require('./../../assets/photos/camps/camps70.jpg') ,
            require('./../../assets/photos/camps/camps71.jpg') ,
            require('./../../assets/photos/camps/camps72.jpg') ,
            require('./../../assets/photos/camps/camps73.jpg') ,
            require('./../../assets/photos/camps/camps74.jpg') ,
            require('./../../assets/photos/camps/camps75.jpg') ,
        ],
    index: null
        })

    }

</script>



<style>

     @import './../../assets/styles/galerie.css';

</style>
