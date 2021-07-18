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
            require('./../../assets/photos/aufträtte/aufträtte1.jpg') ,
            require('./../../assets/photos/aufträtte/aufträtte2.jpg') ,
            require('./../../assets/photos/aufträtte/aufträtte3.jpg') ,
            require('./../../assets/photos/aufträtte/aufträtte4.jpg') ,
            require('./../../assets/photos/aufträtte/aufträtte5.jpg') ,
            require('./../../assets/photos/aufträtte/aufträtte6.jpg') ,
            require('./../../assets/photos/aufträtte/aufträtte7.jpg') ,
            require('./../../assets/photos/aufträtte/aufträtte8.jpg') ,
            require('./../../assets/photos/aufträtte/aufträtte9.jpg') ,
            require('./../../assets/photos/aufträtte/aufträtte10.jpg'),
            require('./../../assets/photos/aufträtte/aufträtte11.jpg') ,
            require('./../../assets/photos/aufträtte/aufträtte12.jpg') ,
            require('./../../assets/photos/aufträtte/aufträtte13.jpg') ,
            require('./../../assets/photos/aufträtte/aufträtte14.jpg') ,
            require('./../../assets/photos/aufträtte/aufträtte15.jpg') ,
            require('./../../assets/photos/aufträtte/aufträtte16.jpg') ,
            require('./../../assets/photos/aufträtte/aufträtte17.jpg') ,
            require('./../../assets/photos/aufträtte/aufträtte18.jpg') ,
            require('./../../assets/photos/aufträtte/aufträtte19.jpg') ,
            require('./../../assets/photos/aufträtte/aufträtte20.jpg') ,
            require('./../../assets/photos/aufträtte/aufträtte21.jpg') ,
            require('./../../assets/photos/aufträtte/aufträtte22.png') ,
            require('./../../assets/photos/aufträtte/aufträtte23.jpg') ,
            require('./../../assets/photos/aufträtte/aufträtte24.png') ,
            require('./../../assets/photos/aufträtte/aufträtte25.jpg') ,
            require('./../../assets/photos/aufträtte/aufträtte26.jpg') ,
            require('./../../assets/photos/aufträtte/aufträtte27.jpg') ,
            require('./../../assets/photos/aufträtte/aufträtte28.png') ,
            require('./../../assets/photos/aufträtte/aufträtte29.jpg') ,
            require('./../../assets/photos/aufträtte/aufträtte30.png') ,
            require('./../../assets/photos/aufträtte/aufträtte31.png') ,
            require('./../../assets/photos/aufträtte/aufträtte32.png') ,
            require('./../../assets/photos/aufträtte/aufträtte33.png') ,
            require('./../../assets/photos/aufträtte/aufträtte34.png') ,
            require('./../../assets/photos/aufträtte/aufträtte35.png') ,
            require('./../../assets/photos/aufträtte/aufträtte36.png') ,
            require('./../../assets/photos/aufträtte/aufträtte37.png') ,
            require('./../../assets/photos/aufträtte/aufträtte38.png') ,
            require('./../../assets/photos/aufträtte/aufträtte39.png') ,
            require('./../../assets/photos/aufträtte/aufträtte40.png') ,
            require('./../../assets/photos/aufträtte/aufträtte41.png') ,
            require('./../../assets/photos/aufträtte/aufträtte42.png') ,
            require('./../../assets/photos/aufträtte/aufträtte43.png') ,
            require('./../../assets/photos/aufträtte/aufträtte44.png') ,
            require('./../../assets/photos/aufträtte/aufträtte45.png') ,
            require('./../../assets/photos/aufträtte/aufträtte46.png') ,
            require('./../../assets/photos/aufträtte/aufträtte47.png') ,
            require('./../../assets/photos/aufträtte/aufträtte48.png') ,
            require('./../../assets/photos/aufträtte/aufträtte49.png') ,
            require('./../../assets/photos/aufträtte/aufträtte50.png') ,
            require('./../../assets/photos/aufträtte/aufträtte51.png') ,
            require('./../../assets/photos/aufträtte/aufträtte52.png') ,
            require('./../../assets/photos/aufträtte/aufträtte53.png') ,
            require('./../../assets/photos/aufträtte/aufträtte54.png') ,
            require('./../../assets/photos/aufträtte/aufträtte55.png') ,
            require('./../../assets/photos/aufträtte/aufträtte56.png') ,
            require('./../../assets/photos/aufträtte/aufträtte57.png') ,
            require('./../../assets/photos/aufträtte/aufträtte58.png') ,
            require('./../../assets/photos/aufträtte/aufträtte59.png') ,
            require('./../../assets/photos/aufträtte/aufträtte60.png') ,
            require('./../../assets/photos/aufträtte/aufträtte61.png') ,
            require('./../../assets/photos/aufträtte/aufträtte62.png') ,
            require('./../../assets/photos/aufträtte/aufträtte63.png') ,
            require('./../../assets/photos/aufträtte/aufträtte64.png') ,
            require('./../../assets/photos/aufträtte/aufträtte65.jpg') ,
            require('./../../assets/photos/aufträtte/aufträtte66.jpg') ,
            require('./../../assets/photos/aufträtte/aufträtte67.jpg') ,
            require('./../../assets/photos/aufträtte/aufträtte68.jpg') ,
            require('./../../assets/photos/aufträtte/aufträtte69.jpg') ,
            require('./../../assets/photos/aufträtte/aufträtte70.jpg') ,
            require('./../../assets/photos/aufträtte/aufträtte71.jpg') ,
            require('./../../assets/photos/aufträtte/aufträtte72.jpg') ,
            require('./../../assets/photos/aufträtte/aufträtte73.jpg') ,
            require('./../../assets/photos/aufträtte/aufträtte74.jpg') ,
            require('./../../assets/photos/aufträtte/aufträtte75.jpg') ,
            require('./../../assets/photos/aufträtte/aufträtte76.jpg') ,
        ],
    index: null
        })

    }

</script>



<style>

     @import './../../assets/styles/galerie.css';

</style>