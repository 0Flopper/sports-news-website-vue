<template>
    <header class="flex bg-white w-full justify-center font-DM-Sans">

        <div class="flex py-6 justify-between items-center w-[1170px]">
            <!-- Logo -->
            <img src="@/assets/sportnews.svg" alt="Logo">

            <!-- Nav Bar -->
            <nav>
                <ul class="flex text-[rgba(38,38,38,0.5)] text-base">
                    <li v-for="item in Menu" :key="item.name">
                        <a :href="item.href"
                            :class="{'font-bold text-black': item.name === 'Home'}" 
                            class="block whitespace-nowrap px-4"
                        >
                            {{ item.name }}
                        </a>
                    </li>
                </ul>
            </nav>

            <!-- Search Button -->
            <button class="rounded-lg w-24 h-9 bg-[#B8C2CE]">
                <span class="flex justify-center items-center">
                    <!-- Search Icon -->
                    <Search size="16" color="white" class="mr-1.5"/>
                    <p class="text-white text-sm">Search</p>
                </span>
            </button>    
        </div>
        
    </header>
</template>

<script setup>
// Lucide Icons
import { Search } from 'lucide-vue-next';

// Defining the navbar items
import { ref } from 'vue';
    const Menu =ref([
        {name:'Home' ,href:'#home'},
        {name:'Category' ,href:'#category'},
        {name:'Trending News' ,href:'#trending-news'},
        {name:'Recent News' ,href:'#recent-news'},
        {name:'Clubs Ranking' ,href:'#clubs-ranking'},
        {name:'Sports Article' ,href:'#sports-article'},
    ]);
</script>