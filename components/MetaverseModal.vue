<template>
    <div class="modal-overlay">
        <div class="flex items-center justify-center">
            <div class="rounded-lg bg-hlb-primary-900 mx-8 px-8 py-6">
                <h2 class="text-white font-bold text-xl ">Want to teleport to your Metaverse?</h2>
            <a href="https://www.spatial.io/s/railzans-Next-Scene-635d09bcf3ac5700012e4bf8?share=5114978034946661921" target="_blank">
                <button class="mt-12 bg-hlb-secondary-500 w-full py-1 text rounded-full text-white">Teleport</button>
            </a>
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
</style>