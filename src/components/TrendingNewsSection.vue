<template>
    <section class="flex flex-col justify-center items-center py-8 px-14 my-8 bg-[#E1E8F0] font-DM-Sans">
        <!-- Tittle -->
        <h1 class="font-medium text-2xl w-full">Trending News</h1>

        <div class="flex w-full">
            
            <div class="flex flex-col gap-6 pt-6 pr-20">
                <!-- Race Horse -->
                <div class="flex justify-center items-center">
                    <img src="@/assets/racehorse.svg" alt="Race Horse">
                    <div class="flex flex-col gap-2 ml-6">
                        <h1 class="font-light text-xs">Race98 - 03 June 2023</h1>
                        <h2 class="font-bold text-base text-black">6-Year-Old Horse Dies at Belmont Park After Race Injury</h2>
                        <h3 class="font-light text-sm">NEW YORK—A 6-year-old horse died after being injured in a race at Belmont Park ahead of next week’s</h3> 
                    </div>
                </div>

                <!-- Cyclist Leads -->
                <div class="flex justify-center items-center">
                    <img src="@/assets/cyclistleads.svg" alt="Cyclist Leads">
                    <div class="flex flex-col gap-2 ml-6">
                        <h1 class="font-light text-xs">Jony.Ls - 03 June 2023</h1>
                        <h2 class="font-bold text-base text-black">Savilia Blunk Embraces Longer Season with World Cup</h2>
                        <h3 class="font-light text-sm">Last year, Savilia Blunk took a more conservative approach to her first season as an Elite Class athlete, skipping some</h3> 
                    </div>
                </div>
                
                <!-- Boxing Arena -->
                <div class="flex justify-center items-center">
                    <img src="@/assets/boxingarena.svg" alt="Boxing Arena">
                    <div class="flex flex-col gap-2 ml-6">
                        <h1 class="font-light text-xs">King.F - 03 June 2023</h1>
                        <h2 class="font-bold text-base text-black">Ryan Garcia is fighting again, this time on social media</h2>
                        <h3 class="font-light text-sm">Boxing star Ryan Garcia and his promoter, Hall of Fame fighter Oscar De La Hoya, reignited their war of words via Twitter on</h3> 
                    </div>
                </div>    
            </div>

            <div class="flex p-8 justify-between flex-col w-[65%] bg-trendingSection text-[#EBEEF3]">

                <div>
                    <button class=" rounded-sm outline-1 py-1 px-4 outline-[#EBEEF3]">
                        <p>Cycling</p>
                    </button>
                </div>

                <div class="flex flex-col">
                    <h1 class=" text-balance">Debits - 03 June 2023</h1>
                    <h2 class="font-bold text-2xl">DISCOVER THE MEMBER BENEFITS OF USA CYCLING!</h2>    
                </div>
                
            </div>
        </div>


    </section>
</template>