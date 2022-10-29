<template>
    <div class="px-6 pt-16">
        <div>
            <h1 class="mb-3 text-2xl" style="font-weight : 300; color: #1E1E1E">
                YOUR ACCOUNTS
            </h1>
            <button class="border rounded-full px-6">HL Basic Savings A/C</button>
            <h2 class="mt-6 text-4xl mb-8">RM 3,190.40</h2>
        </div>

        <NuxtLink to="/">
            <div class="p-3 rounded flex w-full" style="background-color : #4D64FF;">
                <div>
                    <div style="font-size : 16px" class="mt-1 text-white">
                        The 'Art' of You
                    </div>
                    <div class="pb-3 text-white" style="font-size : 10px;">
                        Hawkie has prepared your monthly account highlights
                    </div>
                </div>

                <div>
                    <img class="h-20" src="../static/pngwing 1.png">
                </div>
            </div>
        </NuxtLink>

        <div class="mt-10 flex justify-between">
            <div class=" text-lg" style="font-size : 18px; font-weight : 300; color: #1E1E1E">Recent Transactions</div>
            <NuxtLink to="/">
                <div class="text-xs mt-1 rounded text-white pl-2 pr-2 pb-1 pt-1" style="background-color : #293EC7 ">
                    Download Statement</div>
            </NuxtLink>
        </div>

        <div class="mb-6">
            <div class="mt-6 mb-5" style="color :#4D64FF ">
                Today
            </div>
            <div class="flex flex-col space-y-2">
                <div class="flex">
                    <div class="flex flex-col w-3/4">
                        <div>GRAB RIDES-EC</div>
                        <div class="text-xs">Taxi & Limousines</div>

                    </div>
                    <div class="w-1/4" style="color :#DB0A0A">-RM 25.40</div>
                </div>
                <div class="flex">
                    <div class="flex flex-col w-3/4">
                        <div>AiAsia Sdn Bhd</div>
                        <div class="text-xs">Travel</div>

                    </div>
                    <div class="w-1/4 " style="color :#DB0A0A">-RM 510.00</div>
                </div>
                <div class="flex">
                    <div class="flex flex-col w-3/4">
                        <div>Tony Roma's</div>
                        <div class="text-xs">Food and Beverages</div>

                    </div>
                    <div class="w-1/4 " style="color :#DB0A0A">-RM 98.10</div>
                </div>
            </div>
        </div>

        <div class="mb-6">
            <div style="color : #4D64FF" class="mb-5">Yesterday</div>
            <div class="flex flex-col space-y-2">
                <div class="flex">
                    <div class="flex flex-col w-3/4">
                        <div>Payroll-09220912738</div>
                        <div class="text-xs">Others</div>
                    </div>

                    <div class="w-1/4 " style="color :#0ADB5E">RM 7,800.00</div>
                </div>
                <div class="flex">
                    <div class="flex flex-col w-3/4">
                        <div>Village Grocer</div>
                        <div class="text-xs">Food and Grocery</div>
                    </div>

                    <div class="w-1/4 " style="color :#DB0A0A">- RM 45.20</div>
                </div>
                <div class="flex">
                    <div class="flex flex-col w-3/4">
                        <div>GRAB RIDES-EC</div>
                        <div class="text-xs">Taxi & Limousines</div>
                    </div>

                    <div class="w-1/4 " style="color :#DB0A0A">- RM 14.00</div>
                </div>
            </div>
        </div>
    </div>



</template>

<script>
export default {
    name: 'AccountPage'
}
</script>

<style>

</style>