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
      require("./../../assets/photos/silvester/silvester1.jpg"),
      require("./../../assets/photos/silvester/silvester2.jpg"),
      require("./../../assets/photos/silvester/silvester3.jpg"),
      require("./../../assets/photos/silvester/silvester4.jpg"),
      require("./../../assets/photos/silvester/silvester5.jpg"),
      require("./../../assets/photos/silvester/silvester6.jpg"),
      require("./../../assets/photos/silvester/silvester7.jpg"),
      require("./../../assets/photos/silvester/silvester8.jpg"),
      require("./../../assets/photos/silvester/silvester9.jpg"),
      require("./../../assets/photos/silvester/silvester10.jpg"),
      require("./../../assets/photos/silvester/silvester11.jpg"),
      require("./../../assets/photos/silvester/silvester12.jpg"),
      require("./../../assets/photos/silvester/silvester13.jpg"),
      require("./../../assets/photos/silvester/silvester14.jpg"),
      require("./../../assets/photos/silvester/silvester15.jpg"),
      require("./../../assets/photos/silvester/silvester16.jpg"),
      require("./../../assets/photos/silvester/silvester17.jpg"),
      require("./../../assets/photos/silvester/silvester18.jpg"),
      require("./../../assets/photos/silvester/silvester19.jpg"),
      require("./../../assets/photos/silvester/silvester20.jpg"),
      require("./../../assets/photos/silvester/silvester21.jpg")
    ],
    index: null
  })
};
</script>



<style>
@import "./../../assets/styles/gallery.css";
</style>