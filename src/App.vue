<template >
  <div class="flex flex-col items-center justify-center">
    <NavBar />
    <HeroSection />
    <CategorySection />
    <TrendingNewsSection />  
  </div>
  

</template>

<script setup>
import NavBar from "@/components/NavBar.vue";
import HeroSection from "@/components/HeroSection.vue";
import CategorySection from "@/components/CategorySection.vue";
import TrendingNewsSection from "@/components/TrendingNewsSection.vue";
</script>
