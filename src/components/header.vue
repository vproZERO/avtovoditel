<template>
    <div class="header_box bg-[#19181C] w-[100%] z-40 relative relative overflow-x-hidden">


        <div class="header_box2  2xl:hidden block  mx-auto  ">
            <div class="res_box w-[390px] mx-auto">
                <a class="block w-[70px] mb-[16px] pt-[10px] pl-[10px]" href="#">
                    <img src="../assets/logo.svg" alt="logo">
                </a>
                <div class="px-[10px]">
                    <div class="mb-[30px]">
                        <div class="border-b-[1px] border-white border-opacity-[10%] pb-[20px] mb-[20px]">
                            <div>
                                <p class="text-white text-[24px] font-black uppercase mb-[15px]">Hech qanday qo'rquv  va stresslarsiz Mashina haydashni o'rganing!</p>
                                <div class="flex items-center gap-[10px]">
                                    <div class="rounded-[8px] py-[5px] px-[15px] bg-[#323E55]">
                                        <p class="font-medium text-[14px] text-white">B kategoriyasi uchun boshlang'ich to'lov 1 160 000 so'mdan 0% nasiya </p>
                                    </div>
                                    <div class="rounded-[8px] py-[5px] px-[15px] bg-[#323E55]">
                                        <p class="font-medium text-[14px] text-white">Haftada 6 kun </p>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="border-b-[1px] border-white border-opacity-[10%] pb-[20px] mb-[30px]">
                            <div>
                                <div class="flex items-center gap-[30px] mb-[30px]">
                                    <div class="w-[110px]">
                                        <div class="w-[40px] h-[40px] mb-[8px]">
                                            <img src="../assets/h1.svg" alt="img">
                                        </div>
                                        <p class="text-white text-[16px] font-medium">XX yillik tajriba</p>
                                    </div>
                                    <div>
                                        <div class="w-[40px] h-[40px] mb-[8px]">
                                            <img src="../assets/h2.svg" alt="img">
                                        </div>
                                        <p class="text-white text-[16px] font-medium">Eng yaxshi o'qitish usuli</p>
                                    </div>
                                </div>
                                <div class="flex items-center gap-[30px]">
                                    <div class="w-[110px]">
                                        <div class="w-[40px] h-[40px] mb-[8px]">
                                            <img src="../assets/h3.svg" alt="img">
                                        </div>
                                        <p class="text-white text-[16px] font-medium">Online format</p>
                                    </div>
                                    <div>
                                        <div class="w-[40px] h-[40px] mb-[8px]">
                                            <img src="../assets/h4.svg" alt="img">
                                        </div>
                                        <p class="text-white text-[16px] font-medium">Toshkent bo'yicha 7 ta fillial</p>
                                    </div>
                                </div>
                            </div>
                        </div>
    
                        <div>
                            <p class="text-center text-white text-[12px] font-medium mb-[8px]">Hoziroq ariza qoldiring va 10% chegirmaga ega bo'ling</p>
                            <button v-on:click="isOpen = !isOpen" class="bg-[#407BFF] hover:bg-[#2C5AC2] rounded-[50px] py-[14px] w-full mb-[60px]">
                                <p class="text-white text-[16px] font-medium text-center" >Ariza qoldirish</p>
                            </button>
                            <div class="absolute bottom-0  left-0 mt-[20px] bg-[#2B2B31] w-full py-[10px]">
                                <p class="text-center text-white text-[13px] font-medium">Xonalarimiz eshiklari siz uchun ochiq</p>
                            </div>
                        </div>
                    </div>
                </div>

            </div>
        </div>



        <div class=" 2xl:w-[859px] pb-[137px] mx-auto 2xl:block hidden">
            <div class="flex items-start justify-between mb-[62px]">
                <a href="#">
                    <img src="../assets/logo.svg" alt="logo">
                </a>
                <div class="bg-[#FFFFFF] py-[10px] px-[20px] bg-opacity-[10%] rounded-b-[4px]">
                    <p class="text-[#D8E1FF] text-[20px] gont-medium">Xonalarimiz eshiklari siz uchun ochiq</p>
                </div>
            </div>

            <div>
                <div class="mb-[70px]">
                    <div class="mb-[50px]">
                        <p class="mb-[20px] font-black text-[50px] w-[746px] uppercase text-white">Hech qanday qo'rquv va stresslarsiz Mashina haydashni o'rganing!</p>
                        <div class="flex items-center justify-between">
                            <div class="bg-[#407BFF] rounded-[8px] py-[10px] px-[15px] ">
                                <p class="text-white text-[20px] font-normal">B kategoriyasi uchun boshlang'ich to'lov 1 160 000 so'mdan 0% nasiya </p>
                            </div>
                            <div class="bg-[#407BFF] rounded-[8px] py-[10px] px-[15px] ">
                                <p class="text-white text-[20px] font-normal">Haftada 6 kun</p>
                            </div>
                        </div>
                    </div>
                    <div>
                        <div class="flex items-center gap-[30px] mb-[30px]">
                            <div class="flex items-center gap-[15px] w-[208px]">
                                <div>
                                    <img src="../assets/h1.svg" alt="img">
                                </div>
                                <p class="text-white text-[20px] font-medium">XX yillik tajriba</p>
                            </div>
                            <div class="flex items-center gap-[15px]">
                                <div>
                                    <img src="../assets/h2.svg" alt="img">
                                </div>
                                <p class="text-white text-[20px] font-medium">Eng yaxshi o'qitish usuli</p>
                            </div>
                        </div>
                        <div class="flex items-center gap-[30px] mb-[30px]">
                            <div class="flex items-center gap-[15px] w-[208px]">
                                <div>
                                    <img src="../assets/h3.svg" alt="img">
                                </div>
                                <p class="text-white text-[20px] font-medium">Online format</p>
                            </div>
                            <div class="flex items-center gap-[15px]">
                                <div>
                                    <img src="../assets/h4.svg" alt="img">
                                </div>
                                <p class="text-white text-[20px] font-medium">Toshkent bo'yicha 7 ta fillial</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="flex items-center bg-[#FFFFFF] bg-opacity-[5%] rounded-[52px]  2xl:w-[746px] justify-between aos-animate"  data-aos-duration="1500">
                    <p class="text-white text-[20px] text-medium py-[15px] pl-[20px]">Hoziroq ariza qoldiring va 10% chegirmaga ega bo'ling</p>
                    <button v-on:click="isOpen = !isOpen" class="bg-[#407BFF] hover:bg-[#2C5AC2] rounded-[52px] py-[15px] px-[30px] ">
                        <p class="text-white text-[20px] font-medium text-center" >Ariza qoldirish</p>
                    </button>
                </div>
            </div>
        </div>

        <div class="fixed top-0 bottom-0 left-0 right-0 bg-black bg-opacity-[50%] overflow-hidden " v-if="isOpen">
            <div class="header_modal bg-white 2xl:w-[450px] w-[353px] h-[315px] mx-auto 2xl:h-[405px] mx-auto 2xl:mt-[10%] mt-[234px] p-[20px] rounded-[12px] 2xl:py-[40px] 2xl:px-[30px] relative">
                <button v-on:click="isOpen = !isOpen" class="absolute top-[-30px] right-0">
                    <img src="../assets/plus.svg" alt="plus">
                </button>

                <h1 class="text-center 2xl:text-[24px] text-[20px] font-semibold mb-[3px]">Telefon raqamingizni qoldiring</h1>
                <p class="text-center text-[#BABABA] 2xl:text-[18px] text-[16px] mb-[20px]">Biz siz bilan albatta bog'lanamiz</p>
                <form >
                    <input class="border-b-[1px] border-[#E0E0E0] w-full 2xl:mb-[50px] mb-[40px]" type="text" id="name" name="name" placeholder="Ism">
                    <input class="border-b-[1px] border-[#E0E0E0] w-full mb-[50px] " type="tel" id="tel" name="tel" placeholder="Raqamingiz">
                </form>
                <button class="w-full py-[14px] bg-[#407BFF] rounded-[50px] 2xl:rounded-[52px] 2xl:py-[15px]">
                    <p class="text-white 2xl:text-[20px] font-medium text-center text-[16px]">Ariza qoldirish</p>
                </button>
            </div>
        </div>

        <div class="absolute bottom-0 right-0 w-[448px] 2xl:block hidden " >
            <img src="../assets/carvector.png" alt="">
        </div>
    </div>
</template>
<script>
export default {
    data : () => {
        return {
            isOpen: false
        }
    },
    mounted() {
        setTimeout(() => {
            this.isOpen = true
        },1000);
    },
}
</script>
<style scoped>
    .header_box{
        background-image: url('../assets/header-bg.png') , url('../assets/blurcolor.png');
        background-repeat: no-repeat;
        background-size: cover;
    }
    .header_modal{
        transition: all 0.4s linear;

    }
    @media screen and (max-width: 1535px) {
        .header_box{
        background-image: none;
    }
        .header_box2{
            background-image: url('../assets/blurcolor2.png');
            background-repeat: no-repeat;
            background-size: cover;
            background-position-x: center;

        }
        .res_box{
            
            background-image: url('../assets/header-bg2.png');
            background-repeat: no-repeat;
            background-position-x: right;
            background-position-y: top;
        }
    }
</style>