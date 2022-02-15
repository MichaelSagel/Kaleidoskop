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
      require("./../../assets/photos/camps/camps32.jpg"),
      require("./../../assets/photos/camps/camps31.jpg"),
      require("./../../assets/photos/camps/camps30.jpg"),
      require("./../../assets/photos/camps/camps29.jpg"),
      require("./../../assets/photos/camps/camps28.jpg"),
      require("./../../assets/photos/camps/camps27.jpg"),
      require("./../../assets/photos/camps/camps26.jpg"),
      require("./../../assets/photos/camps/camps25.jpg"),
      require("./../../assets/photos/camps/camps24.jpg"),
      require("./../../assets/photos/camps/camps23.jpg"),
      require("./../../assets/photos/camps/camps22.jpg"),
      require("./../../assets/photos/camps/camps21.png"),
      require("./../../assets/photos/camps/camps20.png"),
      require("./../../assets/photos/camps/camps19.png"),
      require("./../../assets/photos/camps/camps18.png"),
      require("./../../assets/photos/camps/camps17.png"),
      require("./../../assets/photos/camps/camps16.png"),
      require("./../../assets/photos/camps/camps15.png"),
      require("./../../assets/photos/camps/camps14.png"),
      require("./../../assets/photos/camps/camps13.png"),
      require("./../../assets/photos/camps/camps12.png"),
      require("./../../assets/photos/camps/camps11.jpg"),
      require("./../../assets/photos/camps/camps10.jpg"),
      require("./../../assets/photos/camps/camps9.jpg"),
      require("./../../assets/photos/camps/camps8.jpg"),
      require("./../../assets/photos/camps/camps7.jpg"),
      require("./../../assets/photos/camps/camps6.jpg"),
      require("./../../assets/photos/camps/camps5.jpg"),
      require("./../../assets/photos/camps/camps4.jpg"),
      require("./../../assets/photos/camps/camps3.jpg"),
      require("./../../assets/photos/camps/camps2.jpg"),
      require("./../../assets/photos/camps/camps1.jpg")
    ],
    index: null
  })
};
</script>



<style>
@import "./../../assets/styles/gallery.css";
</style>
