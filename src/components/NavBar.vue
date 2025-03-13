<template>
    <header class="flex justify-between items-center p-4 bg-primary">
        <img src="@/assets/SportNews.svg" alt="Logo">
        <nav>
            <ul class="flex text-[rgba(38,38,38,0.5)] text-base font-normal">
                <li v-for="item in Menu" :key="item.name">
                    <a :href="item.href"
                        class="block whitespace-nowrap px-4 "
                    >
                        {{ item.name }}
                    </a>
                </li>
            </ul>
        </nav>
        <button class=" rounded-lg w-24 h-9 flex justify-center items-center bg-[#B8C2CE] text-sm">
            <div>
                O
            </div>
            <div>
                login
            </div>
        </button>
    </header>
</template>

<script setup>
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