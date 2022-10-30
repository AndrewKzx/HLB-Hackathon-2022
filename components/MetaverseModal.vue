<template>
    <div class="modal-overlay">

        <div class="rounded-lg w-full h-56 bg-hlb-primary-900 mx-8 mt-64">
            <div class="">
                <div class="relative h-12 w-full bg-hlb-primary-900 rounded-lg">
                    <svg class="waves" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"
                        viewBox="0 24 150 28" preserveAspectRatio="none" shape-rendering="auto">
                        <defs>
                            <path id="gentle-wave"
                                d="M-160 44c30 0 58-18 88-18s 58 18 88 18 58-18 88-18 58 18 88 18 v44h-352z" />
                        </defs>
                        <g class="parallax">
                            <use xlink:href="#gentle-wave" x="48" y="0" fill="#293EC7" />
                            <use xlink:href="#gentle-wave" x="48" y="3" fill="#4D64FF" />
                            <use xlink:href="#gentle-wave" x="48" y="5" fill="#2031A1" />
                            <use xlink:href="#gentle-wave" x="48" y="7" fill="#E30909" />
                        </g>
                    </svg>
                </div>
                <div class="flex flex-col items-center justify-center px-8 py-6 w-full">
                    <h2 class="text-white font-bold text-xl ">Want to teleport to your Metaverse?</h2>
                <a class='w-full' href="https://www.spatial.io/s/railzans-Next-Scene-635d09bcf3ac5700012e4bf8?share=5114978034946661921"
                    target="_blank">
                    <button
                        class="mt-12 bg-hlb-secondary-500 w-full py-1 text rounded-full text-white ">Teleport</button>
                </a>
                </div>
                
            </div>
        </div>
        <!-- <div class="modal mx-8 px-8">
            
        </div> -->
    </div>
</template>
  
<script>
export default {
}
</script>

<style scoped>
.modal-overlay {
    position: fixed;
    top: 0;
    bottom: 0;
    left: 0;
    right: 0;
    display: flex;
    justify-content: center;
    background-color: #454141da;
    z-index: 1000;
}

.modal {
    text-align: center;
    background-color: #030B56;
    height: 300px;
    width: 500px;
    margin-top: 50%;
    padding: 60px 0;
    border-radius: 20px;
    z-index: 100;
}

.close {
    margin: 10% 0 0 16px;
    cursor: pointer;
}

.close-img {
    width: 25px;
}

.check {
    width: 150px;
}


.modal-fade-enter,
.modal-fade-leave-to {
    opacity: 0;
}

.modal-fade-enter-active,
.modal-fade-leave-active {
    transition: opacity 0.5s ease;
}

/* Waves */
.waves {
    position: relative;
    width: 100%;
    height: 15vh;
    margin-bottom: -7px;
    /*Fix for safari gap*/
    min-height: 100px;
    max-height: 150px;
}

.parallax>use {
    animation: move-forever 25s cubic-bezier(.95, .5, .45, .5) infinite;
}

.parallax>use:nth-child(1) {
    animation-delay: -2s;
    animation-duration: 7s;
}

.parallax>use:nth-child(2) {
    animation-delay: -3s;
    animation-duration: 10s;
}

.parallax>use:nth-child(3) {
    animation-delay: -4s;
    animation-duration: 13s;
}

.parallax>use:nth-child(4) {
    animation-delay: -5s;
    animation-duration: 20s;
}

@keyframes move-forever {
    0% {
        transform: translate3d(-90px, 0, 0);
    }

    100% {
        transform: translate3d(85px, 0, 0);
    }
}

/*Shrinking for mobile*/
@media (max-width: 768px) {
    .waves {
        height: 40px;
        min-height: 40px;
    }
}
</style>