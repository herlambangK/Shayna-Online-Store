<template>
  <div class="home">
    <HeaderShayna />
    <HeroShayna />
    <WomenShayna />
    <InstaShayna />
    <PatnerShayna />
    <FooterShayna />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";
//melakukan exspoert dan jangn lupa menuliskan code <nama />
// import carousel from "vue-owl-carousel"; -> dipindah ke heroshayna
import HeaderShayna from "@/components/HeaderShayna.vue"; //setelah meinport dan exsport dapat langung
import HeroShayna from "@/components/HeroShayna.vue";
import WomenShayna from "@/components/WomenShayna.vue";
import InstaShayna from "@/components/InstaShayna.vue";
import PatnerShayna from "@/components/PatnerShayna.vue";
import FooterShayna from "@/components/FooterShayna.vue";

export default {
  name: "Home",
  components: {
    HeaderShayna,
    HeroShayna,
    WomenShayna,
    InstaShayna,
    PatnerShayna,
    FooterShayna
  }
};
</script>
