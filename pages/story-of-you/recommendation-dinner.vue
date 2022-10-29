<template>
    <div class="bg-hlb-primary-500 h-screen pt-12">

        <!-- Traveller Card -->
        <div class="flex  px-6">
            <div class="w-1/3">
                <img class="rounded border border-yellow-300" src="~/assets/img/dinner.webp" />
            </div>
            <div class="w-2/3 pl-6">
                <h2 class="text-xl text-white font-semibold tracking-wider">A Gastronomical Adventure</h2>
                <p class="mt-2 text-white font-light text-sm italic"> "Treating yourself to an expensive dinner in Kuala Lumpur"</p>
            </div>
        </div>

        <!-- Hawkie -->
        <div class="mt-12 flex pl-6">
            <h3 class="text-hlb-primary-900 text-lg font-bold leading-tight">Oh, one of Hawkie's friends have something in store for you</h3>
            <img class="h-20 -translate-x-6 -translate-y-3" src="~/assets/img/pngwing 2.png" />
        </div>

        <!-- Emirates -->
        <div class="flex flex-col items-center justify-center px-6">
            <img class="my-4 rounded-lg border border-yellow-300" src="~/assets/img/hotel.jpg" />
            <h3 class="text-hlb-primary-900 text-xl font-bold leading-tight my-2">Stay in Awana Resort Hotel</h3>
            <p class="text-white font-light text-sm italic text-center">15% OFF 
Best Available Rate. Booking Period: Now till 30 August 2022
Staying Period: 1 June to 31 August 2022 </p>

        </div>
        <nuxt-link to="/travel">
            <div name="Next" class="box-border ml-20 mr-20 mt-6 h-12 rounded-xl mb-2 flex justify-center items-center"
                style="background-color: #CA2222">
                <h1 class="text-white text-center">
                    See Next Story
                </h1>
            </div>
        </nuxt-link>
    </div>
</template>
  
<script>
export default {
    name: 'StoryOfYouRecommendationDinnerPage',
    layout: 'StoryOfYou',
}
</script>
  
<style>

</style>