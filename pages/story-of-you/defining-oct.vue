<template>
  <div class = "px-6 pt-10 pb-6 bg-hlb-primary-500 h-screen" >

  <div><p class = "text-4xl text-white mb-5 font-bold tracking-wider leading-relaxed">Defining your <br>October</p></div>

  <div class="my-8">
   <div class ="flex pb-12">
        <div class = "w-1/2 pt-2">
          <img src = "~/assets/img/groceries.webp">
        </div>
        <div class="pl-6">
          <p class = "text-2xl text-white font-semibold">The Grocery<br> Shopper</p>
          <p class ="italic text-white font-light text-sm">"Doing groceries on an October weekend at the village grocer</p>
        </div>
        
    </div>

       <div class ="flex pb-12">
        <div class = "w-1/2 pt-2">
          <img src = "~/assets/img/dinner.webp">
        </div>
        <div class ="pl-6">
         <p class = "text-2xl text-white font-semibold">A Gastronomical <br>Adventure</p> 
          <p class="italic font-light text-sm text-white">Treating yourself to an expensive dinner in Kuala Lumpur"</p>
        </div>
        
    </div>

       <div class ="flex">
        <div class = "w-1/2 pt-2">
          <img src = "~/assets/img/travel.webp">
        </div>
        <div class = "pl-6">
          <p class = "text-2xl text-white font-semibold">The Avid <br>Traveller</p>
          <p class="italic font-light text-sm text-white">"Travelling to Vietname in October during the monsoon season"</p>
        </div>
        
    </div>

    <nuxt-link to ="anthology">
    <div class = "box-border mt-20 flex bg-red-500 rounded-full w-3/4 h-9 justify-center ml-10 items-center">
      <p class = "text-center text-white " >Go to your Anthology</p>
      </div>
    </nuxt-link>

  </div>


  </div>
</template>

<script>
export default {
  layout: 'StoryOfYou'
}
</script>

<style>

</style>