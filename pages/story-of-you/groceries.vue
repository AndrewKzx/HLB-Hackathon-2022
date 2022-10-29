<template>
  <div class="items-center justify-center bg-hlb-primary-500 h-screen">
    <h1 class="text-center p-10 text-white" style="font-size:24px">
        Defining Your October
    </h1>

    <div class="flex justify-center items-center">
        <img class="w-2/3 border-solid border-2 rounded-md" style="border-color: #E5D221" src="~/assets/img/groceries.webp"/>
    </div>

    <h1 class="text-center pl-10 pt-10 pr-10 text-white font-bold" style="font-size:32px">
        Doing The Groceries
    </h1>

    <h1 class="text-center pl-12 pr-12 pb-10 pt-4 text-white font-light italic" style="font-size:18px">
        "Doing groceries on an October Weekend at the village grocer"
    </h1>

    <div name="story" class="box-border ml-6 mr-6 rounded-xl mb-2 " style="background-color: #2031A1"> 
        <div class="pl-4 pr-4 pt-4 pb-2" style="font-size:14px" >
            <h1 class="text-white">You spent <b>RM1110.00</b> on groceries-related expenses</h1>
        </div>

        <div class="pl-4 pr-4 pb-4" style="font-size:14px"> 
            <h1 class="text-white"><b>Village Grocer</b> is the most common grocery you go to</h1>
        </div>
    </div>

    <nuxt-link to="dinner">
    <div name="Next" class="box-border ml-20 mr-20 mt-12 h-12 rounded-xl mb-2 flex justify-center items-center" style="background-color: #CA2222"> 
        
        <h1 class="text-white text-center">
            See Next Story
        </h1>
    </div>
    </nuxt-link>

  </div>
</template>

<script>
export default {
    layout: 'StoryOfYou',
}
</script>

<style>

</style>