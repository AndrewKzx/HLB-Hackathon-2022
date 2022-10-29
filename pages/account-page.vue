<template>
  <div>
      <div class = "mt-20 mb-3 pl-10" style = "font-size : 24px; font-weight : 300; color: #1E1E1E">
          YOUR ACCOUNTS
      </div>
      
      <div class = "pl-6 border pt-1 pb-1 rounded-full mb-2 ml-5" style = "width :250px">HL Basic Savings A/C</div>
        <div class = "pl-10 mt-6 text-4xl mb-8">RM 3,190.40</div>
       <NuxtLink to = "/story-of-you" >
          <div class = "pl-1 rounded ml-5 flex" style = "background-color : #4D64FF; width : 350px; height : 70px ">
              <div class ="pt-3">
                <div style = "font-size : 16px" class = "mt-1 text-white">
                  The 'Art' of You
              </div>
              <div class = "pb-3 text-white" style="font-size : 10px;">
                  Hawkie has prepared your monthly account highlights
              </div>
              </div>

            <div>
            <img src="../static/pngwing 1.png">
            </div>
          </div>
          

      </NuxtLink>
        <div class="mt-10 flex space-x-14 pl-5" >
            <div class =" text-lg" style = "font-size : 18px; font-weight : 300; color: #1E1E1E">Recent Transactions</div>
            <NuxtLink to = "/">
            <div class ="text-xs mt-1 rounded text-white pl-2 pr-2 pb-1 pt-1" style = "background-color : #293EC7 ">Download Statement</div>
            </NuxtLink>
        </div>

        <div class ="ml-5">
            <div class ="mt-6 mb-5" style = "color :#4D64FF ">
                Today
            </div>
            <div class = "flex mb-6">
                <div class = "flex flex-col w-3/4">
                    <div>GRAB RIDES-EC</div>
                    <div class = "text-xs">Taxi & Limousines</div>

                </div>
                <div class = "w-1/4" style = "color :#DB0A0A">-RM 25.40</div>
            </div>
     <div class = "flex mb-6">
                <div class = "flex flex-col w-3/4">
                    <div>AiAsia Sdn Bhd</div>
                    <div class = "text-xs">Travel</div>

                </div>
                <div class = "w-1/4 " style = "color :#DB0A0A">-RM 510.00</div>
            </div>
     <div class = "flex mb-6">
                <div class = "flex flex-col w-3/4">
                    <div>Tony Roma's</div>
                    <div class = "text-xs">Food and Beverages</div>

                </div>
                <div class = "w-1/4 " style = "color :#DB0A0A">-RM 98.10</div>
            </div>
<!--red #DB0A0A G OADB5E -->
            <div style = "color : #4D64FF" class = "mb-5">Yesterday</div>
              <div class ="flex">
                  <div class = "flex flex-col w-3/4">
                      <div>Payroll-09220912738</div>
                      <div class = "text-xs">Others</div>
                  </div>

                <div class = "w-1/4 " style = "color :#0ADB5E">RM 7,80000</div>

            </div>
        </div>


  </div>



</template>

<script>
export default {
    name : 'AccountPage'
}
</script>

<style>

</style>