<template>
    <div class="bg-hlb-primary-500 h-screen pt-12">

        <!-- Traveller Card -->
        <div class="flex  px-6">
            <div class="w-1/3">
                <img class="rounded border border-yellow-300" src="~/assets/img/travel.webp" />
            </div>
            <div class="w-2/3 pl-6">
                <h2 class="text-md text-white font-semibold tracking-wider">The Avid Traveller</h2>
                <p class="mt-2 text-white font-light text-xs italic">“Travelling to Vietnam in October during the
                    monsoon season”</p>
            </div>
        </div>

        <!-- Hawkie -->
        <div class="mt-12 flex pl-6">
            <h3 class="text-hlb-primary-900 text-md font-bold leading-tight">As an Avid Traveller, Hawkie thinks you
                would love...</h3>
            <img class="h-16 -translate-x-2 -translate-y-2" src="~/assets/img/pngwing 2.png" />
        </div>

        <!-- Emirates -->
        <div class="flex flex-col items-center justify-center px-6">
            <img class="" src="~/assets/img/emirates.png" />
            <h3 class="text-hlb-primary-900 text-md font-bold leading-tight my-4">Emirates Credit Card</h3>
            <p class="text-white font-light text-xs italic text-center">Enjoy complimentary flight to Europe, Skywards Miles on
                daily spend, Emirates Skywards Silver membership and many more.</p>
            
            <div class="flex space-x-6 w-full items-start justify-center mt-6">
                <button class="bg-white py-2 px-6 rounded-full text-hlb-primary-700 text-xs">More Details</button>
                <a href="https://www.hlb.com.my/en/form/credit-card.html?icp=hlb-en-promo-cta-tx-cc-q12223" target="_blank">
                    <button class="bg-hlb-secondary-500 py-2 px-6 rounded-full text-white text-xs">Apply Now</button></a>
            </div>
            <button class="bg-hlb-primary-700 py-2 px-12 rounded-full text-white my-8 w-full">See Next Story</button>

        </div>
    </div>
</template>
  
<script>
export default {
    name: 'StoryOfYouRecommendationPage'
}
</script>
  
<style>

</style>