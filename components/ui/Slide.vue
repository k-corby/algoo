<template>
  <Slide right width="1200">
    <AppMenuItems />
  </Slide>
</template>
<script>
import { Slide } from "vue-burger-menu"; // import the CSS transitions you wish to use, in this case we are using `Slide`
export default {
  name: "Slider",
  components: {
    
    Slide,
  },
};
</script>

<style>
.bm-cross-button {
  left: 30vw;
}
</style>