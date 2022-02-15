<template>
  <div id="app" class="photo__container">
    <div class="image-wrapper" v-for="(image, i) in images" :key="i">
      <img class="image" :src="image" @click="index = i" />
    </div>
    <client-only placeholder="Loading...">
      <VueGallerySlideshow
        :images="images"
        :index="index"
        @close="index = null"
      />
    </client-only>
  </div>
</template>


<script>
import VueGallerySlideshow from "vue-gallery-slideshow";

export default {
  components: { VueGallerySlideshow },

  data: () => ({
    images: [
      require("./../../assets/photos/auftritte/auftritte1.png"),
      require("./../../assets/photos/auftritte/auftritte2.jpg"),
      require("./../../assets/photos/auftritte/auftritte3.jpg"),
      require("./../../assets/photos/auftritte/auftritte4.jpg"),
      require("./../../assets/photos/auftritte/auftritte5.jpg"),
      require("./../../assets/photos/auftritte/auftritte6.jpg"),
      require("./../../assets/photos/auftritte/auftritte7.jpg"),
      require("./../../assets/photos/auftritte/auftritte8.jpg"),
      require("./../../assets/photos/auftritte/auftritte9.jpg"),
      require("./../../assets/photos/auftritte/auftritte10.jpg"),
      require("./../../assets/photos/auftritte/auftritte11.jpg"),
      require("./../../assets/photos/auftritte/auftritte12.jpg"),
      require("./../../assets/photos/auftritte/auftritte13.jpg"),
      require("./../../assets/photos/auftritte/auftritte14.jpg"),
      require("./../../assets/photos/auftritte/auftritte15.jpg"),
      require("./../../assets/photos/auftritte/auftritte16.jpg"),
      require("./../../assets/photos/auftritte/auftritte17.png"),
      require("./../../assets/photos/auftritte/auftritte18.png"),
      require("./../../assets/photos/auftritte/auftritte19.jpg"),
      require("./../../assets/photos/auftritte/auftritte20.jpg"),
      require("./../../assets/photos/auftritte/auftritte21.png"),
      require("./../../assets/photos/auftritte/auftritte22.png"),
      require("./../../assets/photos/auftritte/auftritte23.png"),
      require("./../../assets/photos/auftritte/auftritte24.png"),
      require("./../../assets/photos/auftritte/auftritte25.png"),
      require("./../../assets/photos/auftritte/auftritte26.png"),
      require("./../../assets/photos/auftritte/auftritte27.png"),
      require("./../../assets/photos/auftritte/auftritte28.png"),
      require("./../../assets/photos/auftritte/auftritte29.png"),
      require("./../../assets/photos/auftritte/auftritte30.png"),
      require("./../../assets/photos/auftritte/auftritte31.png"),
      require("./../../assets/photos/auftritte/auftritte32.png"),
      require("./../../assets/photos/auftritte/auftritte33.png"),
      require("./../../assets/photos/auftritte/auftritte34.png"),
      require("./../../assets/photos/auftritte/auftritte35.jpg")
    ],
    index: null
  })
};
</script>



<style>
@import "./../../assets/styles/gallery.css";
</style>