<script setup>
import HeaderComponent from "../components/Shared/Header/HeaderComponent.vue";
import Carousel from "@/components/Home/Carousel.vue";
import DonateRequestSidebar from "@/components/Home/Sidebar/DonateRequestSidebar.vue";
import WhatWeAreComponent from "@/components/Home/WhatWeAreComponent.vue";
import CategoryComponent from "@/components/Home/CategoryComponent.vue";
import CampaignSlider from "../components/Home/Campaign/CampaignSlider.vue";
import FooterComponent from "../components/Shared/Footer/FooterComponent.vue";
</script>
<template lang="pug">
HeaderComponent
Carousel
main.container.grid.grid--2-1
  section.section.section--what-we-are
    WhatWeAreComponent
    CategoryComponent
  DonateRequestSidebar
CampaignSlider.container
//- CampaignSlider.container.container--full
FooterComponent
</template>
<style lang="scss"></style>
