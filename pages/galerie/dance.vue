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
            require('./../../assets/photos/dance/dance1.png') ,
            require('./../../assets/photos/dance/dance2.png') ,
            require('./../../assets/photos/dance/dance3.jpg') ,
            require('./../../assets/photos/dance/dance4.jpg') ,
            require('./../../assets/photos/dance/dance5.jpg') ,
            require('./../../assets/photos/dance/dance6.jpg') ,
            require('./../../assets/photos/dance/dance7.jpg') ,
            require('./../../assets/photos/dance/dance8.jpg') ,
            require('./../../assets/photos/dance/dance9.jpg') ,
            require('./../../assets/photos/dance/dance10.jpg') ,
            require('./../../assets/photos/dance/dance11.jpg') ,
            require('./../../assets/photos/dance/dance12.jpg') ,
            require('./../../assets/photos/dance/dance13.jpg') ,
            require('./../../assets/photos/dance/dance14.jpg') ,
            require('./../../assets/photos/dance/dance15.jpg') ,
            require('./../../assets/photos/dance/dance16.jpg') ,
            require('./../../assets/photos/dance/dance17.jpg') ,
            require('./../../assets/photos/dance/dance18.jpg') ,
            require('./../../assets/photos/dance/dance19.jpg') ,
            require('./../../assets/photos/dance/dance20.jpg') ,
            require('./../../assets/photos/dance/dance21.jpg') ,
            require('./../../assets/photos/dance/dance22.jpg') ,
            require('./../../assets/photos/dance/dance23.jpg') ,
            require('./../../assets/photos/dance/dance24.jpg') ,
            require('./../../assets/photos/dance/dance25.jpg') ,
            require('./../../assets/photos/dance/dance26.jpg') ,
            require('./../../assets/photos/dance/dance27.jpg') ,
            require('./../../assets/photos/dance/dance28.jpg') ,
            require('./../../assets/photos/dance/dance29.jpg') ,
            require('./../../assets/photos/dance/dance30.jpg') ,
            require('./../../assets/photos/dance/dance31.jpg') ,
            require('./../../assets/photos/dance/dance32.jpg') ,
            require('./../../assets/photos/dance/dance33.jpg') ,
            require('./../../assets/photos/dance/dance34.jpg') ,
            require('./../../assets/photos/dance/dance35.jpg') ,
            require('./../../assets/photos/dance/dance36.jpg') ,
            require('./../../assets/photos/dance/dance37.jpg') ,
            require('./../../assets/photos/dance/dance38.jpg') ,
            require('./../../assets/photos/dance/dance39.jpg') ,
            require('./../../assets/photos/dance/dance40.jpg') ,
            require('./../../assets/photos/dance/dance41.jpg') ,
            require('./../../assets/photos/dance/dance42.jpg') ,
            require('./../../assets/photos/dance/dance43.jpg') ,
            require('./../../assets/photos/dance/dance44.jpg') ,
            require('./../../assets/photos/dance/dance45.jpg') ,
            require('./../../assets/photos/dance/dance46.jpg') ,
            require('./../../assets/photos/dance/dance47.jpg') ,
            require('./../../assets/photos/dance/dance48.jpg') ,
            require('./../../assets/photos/dance/dance49.jpg') ,
            require('./../../assets/photos/dance/dance50.jpg') ,
            require('./../../assets/photos/dance/dance51.jpg') ,
            require('./../../assets/photos/dance/dance52.jpg') ,
            require('./../../assets/photos/dance/dance53.jpg') ,
            require('./../../assets/photos/dance/dance54.jpg') ,
            require('./../../assets/photos/dance/dance55.jpg') ,
            require('./../../assets/photos/dance/dance56.jpg') ,
            require('./../../assets/photos/dance/dance57.jpg') ,
            require('./../../assets/photos/dance/dance58.jpg') ,
            require('./../../assets/photos/dance/dance59.jpg') ,
            require('./../../assets/photos/dance/dance60.jpg') ,
            require('./../../assets/photos/dance/dance61.jpg') ,
            require('./../../assets/photos/dance/dance62.jpg') ,
            require('./../../assets/photos/dance/dance63.jpg') ,
            require('./../../assets/photos/dance/dance64.jpg') ,
            require('./../../assets/photos/dance/dance65.jpg') ,
            require('./../../assets/photos/dance/dance66.jpg') ,
            require('./../../assets/photos/dance/dance67.jpg') ,
            require('./../../assets/photos/dance/dance68.jpg') ,
            require('./../../assets/photos/dance/dance69.jpg') ,
            require('./../../assets/photos/dance/dance70.jpg') ,
            require('./../../assets/photos/dance/dance71.jpg') ,
            require('./../../assets/photos/dance/dance72.jpg') ,
        ],
    index: null
        })

    }

</script>



<style>

     @import './../../assets/styles/galerie.css';

</style>
