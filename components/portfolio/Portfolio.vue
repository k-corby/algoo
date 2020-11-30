<!--<template>
  <div>
    <p v-for="item in items" :key="item.title">
      {{ item.text }}
    </p>
  </div>
</template>-->
<script>
export default {
  name: "Portfolio",
  data: () => ({
    items: [
      {
        slogan: "Research",
        title: "Identify the current market to build something special.",
        text:
          "Once the brief has been received by the applicant and the market studied, our first reflex is to find out more about its customers: their expectations, their needs, their frustrations.",
        img: "~../assets/img/uploads/research.jpg",
      },
      {
        slogan: "Branding",
        title: "We develop a unique branding experience.",
        text:
          "Branding is an essential component that requires research, prototyping and integration of unique elements to make you stand out from others.",
        img: "~../assets/img/uploads/sketch-hand.jpg",
      },
      {
        slogan: "Prototype",
        title: "Refine ideas to build a unique user experience.",
        text:
          "We teach from experience. Our educators are top-tier freelance web designers who will show you the frameworks they use in their own businesses.",
        img: "~../assets/img/uploads/app-dev.jpg",
      },
      {
        slogan: "Development",
        title: "Custom crafted applications for devices.",
        text:
          "We teach from experience. Our educators are top-tier freelance web designers who will show you the frameworks they use in their own businesses.",
        img: "~../assets/img/uploads/dev-app.jpg",
      },
    ],
  }),
};
</script>