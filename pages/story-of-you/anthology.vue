<template>
  <div class="bg-hlb-primary-500 min-h-screen">
    <metaverse-modal v-show="showModal" @close-modal="showModal = false" />
    <div name="Your Anthology" class=" pl-4 pr-4 pb-3 flex justify-between"> 
        <p class=" w-8 pt-10 flex-none text-3xl text-white"> < </p>
        <h1 class="flex-initial text-center pt-10 text-white font-bold" style="font-size:24px">
            Your Anthology
        </h1>

        <div class="pt-11">
            <img @click="showModal = true" class="flex-initial w-8 h-8" src="~/assets/img/Meta Icon.png" alt="">
        </div>
        
    </div>

    <div class="pt-4 pr-4 pl-6">
        <ol class="relative border-l border-white dark:border-white">                  
            <li class="mb-10 ml-4">
                <div class="absolute w-3 h-3 rounded-full mt-1.5 -left-1.5 border" style="background-color:#293EC7; border-color:#293EC7"></div>
                <a href="#" class="inline-flex items-center focus:outline-none focus:ring-gray-200">
                    
                    <div name="Your October Story">
                        <h1 class="mb-3 font-bold pl-2" style="font-color:#030B56; font-size:20px">Your October Story</h1>
                
                        <div class="box-border x-2/3 rounded-xl mb-2 pt-3 pr-4 pb-2 pl-4" style="background-color: #2031A1">
                        
                            <div name="Travelling Box" class="flex justify-between italic"> 
                                <p class=" text-white pr-4" style="font-size:14px">"Travelling to Vietnam in October during the monsoon season"</p>
                            
                                <img class="x-1/3 w-20 border-solid border-2 rounded-sm" style="border-color: #E5D221" src="~/assets/img/travel.webp" alt="">
                            </div>
                        
                            <div name="Dinner Box" class="flex justify-between pt-4 italic">
                                <p class=" text-white pr-4" style="font-size:14px">"Treating yourself to an expensive dinner in Kuala Lumpur"</p>
                            
                                <img class="x-1/3 w-20 border-solid border-2 rounded-sm" style="border-color: #E5D221" src="~/assets/img/dinner.webp" alt="">
                            </div>
                
                            <div name="Travelling Box" class="flex justify-between pt-4 italic">
                                <p class=" text-white pr-4" style="font-size:14px">"Doing groceries on an October weekend at the village grocer"</p>
                            
                                <img class="x-1/3 w-20 border-solid border-2 rounded-sm" style="border-color: #E5D221" src="~/assets/img/groceries.webp" alt="">
                            </div>
                            
                            <nuxt-link to="groceries">
                                <div name="Revisit Story" class="box-border mt-4 w-1/2 h-9 rounded-full mb-2 flex justify-center items-center" style="background-color: #E30900"> 
                                    
                                    <h1 class="text-white text-center font-light">
                                        Revisit Story
                                    </h1>
                                </div>
                            </nuxt-link>
                        </div>        
                    </div>
                </a>
            </li>
            <li class="mb-10 ml-4">
                <div class="absolute w-3 h-3 bg-gray-200 rounded-full mt-1.5 -left-1.5 border border-white" style="background-color:#293EC7; border-color:#293EC7"></div>
                <a href="#" class="inline-flex items-center focus:outline-none focus:ring-gray-200">
                    
                    <div name="Your September Story" class="pb-2">
                        <h1 class="mb-3 font-bold pl-2" style="font-color:#030B56; font-size:20px">Your September Story</h1>
                
                        <div class="box-border x-2/3 rounded-xl mb-2 pt-3 pr-4 pb-2 pl-4" style="background-color: #2031A1">
                        
                            <div name="Travelling Box" class="flex justify-between italic"> 
                                <p class=" text-white pr-4" style="font-size:14px">"Travelling to Vietnam in October during the monsoon season"</p>
                            
                                <img class="x-1/3 w-20 border-solid border-2 rounded-sm" style="border-color: #E5D221" src="~/assets/img/travel.webp" alt="">
                            </div>
                        
                            <div name="Dinner Box" class="flex justify-between pt-4 italic">
                                <p class=" text-white pr-4" style="font-size:14px">"Treating yourself to an expensive dinner in Kuala Lumpur"</p>
                            
                                <img class="x-1/3 w-20 border-solid border-2 rounded-sm" style="border-color: #E5D221" src="~/assets/img/dinner.webp" alt="">
                            </div>
                
                            <div name="Travelling Box" class="flex justify-between pt-4 italic">
                                <p class=" text-white pr-4" style="font-size:14px">"Doing groceries on an October weekend at the village grocer"</p>
                            
                                <img class="x-1/3 w-20 border-solid border-2 rounded-sm" style="border-color: #E5D221" src="~/assets/img/groceries.webp" alt="">
                            </div>
                            
                            <nuxt-link to="groceries">
                                <div name="Revisit Story" class="box-border mt-4 w-1/2 h-9 rounded-full mb-2 flex justify-center items-center" style="background-color: #E30900"> 
                                    
                                    <h1 class="text-white text-center font-light">
                                        Revisit Story
                                    </h1>
                                </div>
                            </nuxt-link>
                        </div>        
                    </div>


                </a>
            </li>
        </ol> 
    </div>   
  </div>
</template>

<script>

export default {
    layout: 'StoryOfYou',
    data() {
    return {
      showModal: false,
    }
}
}
</script>

<style>

</style>