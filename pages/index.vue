<template>
  <div>
    <div name="Current and Savings" class = "py-12 pl-10 font-medium text-3xl">
      <h1>CURRENT &</h1>
      <h1>SAVINGS</h1>
    </div>
    
    <div class="flex items-center justify-left w-full mb-8">
      <div>
        <h4 class = "text-xs pl-10 pb-2">
          TOTAL EQUIVALENT BALANCE (MYR)
        </h4>
        <span class="text-3xl pl-10">-</span>
      </div>

        <label 
          for="toggle"
          class="flex items-center cursor-pointer pb-10 pl-4"
        >
          <!-- toggle -->
          <div class="relative">
            <!-- input -->
            <input id="toogleA" type="checkbox" class="sr-only" />
            <!-- line -->
            <div class="w-10 h-4 bg-gray-400 rounded-full shadow-inner"></div>
            <!-- dot -->
            <div class="dot absolute w-6 h-6 bg-white rounded-full shadow -left-1 -top-1 transition"></div>
          </div>
          <!-- label -->
          <div class="ml-3 text-gray-700 font-medium">
          </div>
        </label>       
    </div>

    <div> 
      <h1 class = "text-xs pl-10">QUICK PAY</h1>
    </div>

    <div class = "pl-6 pt-2">
      <button class = "border-double border-2 drop-shadow-md m-3 w-12 h-12 rounded-full">
        <h1 class = "text-2xl font-extrabold text-transparent bg-clip-text bg-gradient-to-br from-orange-200 to-red-600">K</h1>
      </button>
      <button class = "border-double border-2 drop-shadow-md m-3 w-12 h-12 rounded-full">
        <h1 class = "text-2xl font-extrabold text-transparent bg-clip-text bg-gradient-to-br from-orange-200 to-red-600">A</h1>
      </button>
      <button class = "border-double border-2 drop-shadow-md m-3 w-12 h-12 rounded-full">
        <h1 class = "text-2xl font-extrabold text-transparent bg-clip-text bg-gradient-to-br from-orange-200 to-red-600">N</h1>
      </button>
      <button class = "border-double border-2 m-3 w-12 h-12 rounded-full">
        <h1 class = "text-xl">></h1>
      </button>
    </div>

    <div class="flex space-x-6 pb-6">
      <h1 class="pl-10">KHOR...</h1> 
      <h1>KHAI...</h1> 
      <h1 class="pl-2">NAZ...</h1> 
    </div>

    <div name="banner"> 

      <div class="box-border h-30 w-90 p-4 ml-10 mr-10 rounded-lg mb-8" style="background-color: #4D64FF">
        <div class="flex col">

          <div>
            <h1 class="font-medium text-white text-sm">Hawkie has something new for you!</h1>
            <h1 class="text-xs text-white">Check out your monthly statement now</h1>
          </div>

          <div>
            <img src="../static/pngwing 1.png" class="pl-70 flex justify-end">
          </div>
          
        </div>
        
      </div>

    </div>
  </div>

</template>

<script>
export default {
  name: 'IndexPage'
}
</script>
