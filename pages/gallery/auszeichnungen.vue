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
      require("./../../assets/photos/auszeichnungen/auszeichnungen1.jpg"),
      require("./../../assets/photos/auszeichnungen/auszeichnungen2.jpg"),
      require("./../../assets/photos/auszeichnungen/auszeichnungen3.jpg"),
      require("./../../assets/photos/auszeichnungen/auszeichnungen4.jpg"),
      require("./../../assets/photos/auszeichnungen/auszeichnungen5.jpg"),
      require("./../../assets/photos/auszeichnungen/auszeichnungen6.png"),
      require("./../../assets/photos/auszeichnungen/auszeichnungen7.png"),
      require("./../../assets/photos/auszeichnungen/auszeichnungen8.png"),
      require("./../../assets/photos/auszeichnungen/auszeichnungen9.png"),
      require("./../../assets/photos/auszeichnungen/auszeichnungen10.jpg")
    ],
    index: null
  })
};
</script>



<style>
@import "./../../assets/styles/gallery.css";
</style>