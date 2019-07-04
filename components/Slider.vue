<template>
  <div class="pt-40 pb-10">
    <el-carousel :interval="4000" type="card" height="450px">
      <el-carousel-item v-for="(image, index) in images" :key="index">
        <div v-bind:style="{ backgroundImage: `url('${image}`}" class="img-slider border-2 border-green-200 m-0"></div>
      </el-carousel-item>
    </el-carousel>
  </div>
</template>
<script>
import path from "path";

export default {
  data() {
    return {
      images: [
        require("~/assets/images/IMG-20190622-WA0062.jpg"),
        require("~/assets/images/IMG-20190622-WA0028.jpg"),
        require("~/assets/images/IMG-20190622-WA0064.jpg"),
        require("~/assets/images/IMG-20190622-WA0029.jpg"),
        require("~/assets/images/IMG-20190622-WA0046.jpg")
      ]
    };
  }
};
</script>

<style>
.el-carousel__item h3 {
  color: #475669;
  font-size: 14px;
  opacity: 0.75;
  line-height: 200px;
  margin: 0;
}

.el-carousel__item:nth-child(2n) {
  background-color: #99a9bf;
}

.el-carousel__item:nth-child(2n + 1) {
  background-color: #d3dce6;
}
</style>
