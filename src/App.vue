<template >
  <NavBar />
  <div class="flex items-center justify-center">
    <div class="flex flex-col w-[1170px]"> 
      <HeroSection />
      <CategorySection />
      <TrendingNewsSection />  
      <FootBallSection />
    </div>
  </div>
  

</template>

<script setup>
import NavBar from "@/components/NavBar.vue";
import HeroSection from "@/components/HeroSection.vue";
import CategorySection from "@/components/CategorySection.vue";
import TrendingNewsSection from "@/components/TrendingNewsSection.vue";
import FootBallSection from "@/components/FootBallSection.vue";
</script>
