<template>
    <section class="flex flex-col w-full">
        <div class="flex bg-[#EBEEF3] flex-col justify-between items-start footballsec w-full h-[518px] text-white py-8 px-10">

            <div class="flex outline-1 rounded-md px-4 py-1">
                <p>FootBall</p>
            </div>

            <div class="flex flex-col w-[60%] gap-2">
                <h1 class=" font-extralight text-sm text-[#F9FAFC]">Agence France-Presse - 04 June 2023</h1>
                <h2 class=" break-keep font-extrabold text-2xl uppercase">Lionel Messi Leaving Ligue 1 Team Paris Saint-Germain, Club Confirms</h2>
                <h3 class="font-light text-balance text-[#F9FAFC]">The EuroLeague Finals Top Scorer is the individual award for the player that gained the highest points in the EuroLeague Finals</h3>
            </div>    
        </div>

        <div class="flex text-black/50 w-full h-12 justify-end items-center pt-4 gap-11">

            <div class="flex bg-[#BAB8B8] p-3 h-full justify-center items-center ">
                <MoveLeft />
            </div>

            <div class="flex bg-black w-7 h-7 rounded-full justify-center items-center">
                <p class="text-xl text-white">1</p>
            </div>
            <p class="text-xl">2</p>
            <p class="text-xl">3</p>
            <p class="text-xl">4</p>

            <div class="flex bg-[#262626] p-3 h-full justify-center items-center ">
                <MoveRight color="#fff"/>
            </div>
        </div>
    </section>
</template>

<script setup>
// Lucide Icons
import { MoveRight  } from 'lucide-vue-next';
import { MoveLeft  } from 'lucide-vue-next';

</script>