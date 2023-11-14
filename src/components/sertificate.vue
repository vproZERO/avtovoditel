<template>
    <div class="py-[50px] 2xl:py-[100px] relative">
        <h1 class="text-[#1B1B35] 2xl:text-[40px] font-bold text-[24px] text-center mb-[30px] 2xl:mb-[70px] ">Sertifikatlar</h1>
        <div class=" 2xl:flex block 2xl:w-full w-[353px] mx-auto items-center justify-center">
            <div class="relative cursor-pointer w-[353px] h-[437px] 2xl:w-[526px] 2xl:h-[652px] ">
                <div v-on:click="isOpen = !isOpen" class="w-[100%] h-[100%] 2xl:hover:bg-black absolute  opacity-0 2xl:hover:opacity-[30%] rounded-[4px] ">
                    <div  class="w-[50px] mx-auto h-[50px] my-[50%]">
                        <img src="../assets/camera.svg" alt="">
                    </div>
                </div>
                <img class="object-contain" src="../assets/sertificate.svg" alt="sertificate">
            </div>
            <div class="relative cursor-pointer w-[353px] h-[437px] 2xl:w-[526px] 2xl:h-[652px] ">
                <div v-on:click="isOpen2 = !isOpen2" class="w-[100%] h-[100%] 2xl:hover:bg-black absolute  opacity-0 2xl:hover:opacity-[30%] rounded-[4px]">
                    <div class="w-[50px] mx-auto h-[50px] my-[50%] z-40">
                        <img src="../assets/camera.svg" alt="">
                    </div>
                </div>
                <img class="object-cover" src="../assets/sertificate2.svg" alt="sertificate">
            </div>


            <div v-if="isOpen" class="absolute inset-0 bg-black bg-opacity-[50%]">
                <div class="2xl:w-[663px] 2xl:mt-[10%] relative w-[353px] 2xl:h-[800px] h-[455px] mt-[40%] mt-[] mx-auto">
                    <button v-on:click="isOpen = !isOpen" class="absolute text-white font-bold text-2xl top-[-30px] right-[-5px]">X</button>
                    <img  src="../assets/sertificate.svg" alt="sertificate">
                </div>
            </div>
            <div v-if="isOpen2" class="absolute inset-0 bg-black bg-opacity-[50%]">
                <div class="2xl:w-[663px] 2xl:mt-[10%] relative w-[353px] 2xl:h-[800px] h-[455px] mt-[100%] mt-[] mx-auto">
                    <button v-on:click="isOpen2 = !isOpen2" class="absolute text-white font-bold text-2xl top-[-30px] right-[-5px]">X</button>
                    <img  src="../assets/sertificate2.svg" alt="sertificate">
                </div>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    data:() => {
        return {
            isOpen: false,
            isOpen2: false
        }
    },
}
</script>
<style lang="">
    
</style>