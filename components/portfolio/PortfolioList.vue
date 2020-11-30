<template>
  <div>
    <div
      v-for="item in data.items"
      :key="item.id"
      class="row-fluid bg-white pb"
    >
      <div class="sticky ar col-span">
        <div class="number">{{ item.id }}</div>
        <h1 class="heading">{{ item.section }}</h1>
      </div>
      <div :style="order" class="ml9vw mr9vw">
        <!--<img src="../../assets/img/uploads/research.jpg" />-->
        <img
          class="scale-crop scale-crop-vw blend-mode"
          :src="require('../../assets/img/uploads/' + item.img)"
        />
      </div>
      <div class="pl pr">
        <h4 class="mt-vw5">
          {{ item.title }}
        </h4>
        <p>
          {{ item.text }}
        </p>
        <p class="mrg-top-50">
          <a class="btn btn-fixed" href="/home/philosophy">Explore &rarr;</a>
        </p>
      </div>
    </div>
  </div>
</template>
<script>
import json from "./data.json";
//import PortfolioData from "../portfolio/Portfolio.vue";
console.log(json);
export default {
  data() {
    return { data: json };
  },
  computed: {
    order: function () {
      return console.log(1);
    },
    //images() {
    //return require("../../assets/img/research.jpg");
    //},
  },
  //async fetch() {
  //this.data = await this.$content(json.CONTENT).fetch();
  // },
};
</script>