<template>
    <div class="2xl:py-[150px] py-[50px]">
        <h1 class="text-center font-bold text-[#1B1B35] text-[24px] 2xl:text-[40px] 2xl:mb-[40px] mb-[15px] aos-init aos-animate " data-aos="fade-up" data-aos-duration="1500">Narxlar</h1>
        <div class="flex items-center 2xl:w-[416px] w-[353px] mx-auto justify-center gap-6 mt-[23px] p-[2px] bg-[#F3F3F3] rounded-lg">
            <h2 class="text-[14px]  2xl:text-[16px] 2xl:leading-[18px] 2xl:py-[14px] 2xl:px-[12px] 2xl:w-[206px] w-[174px] px-[12px] py-[6px] rounded-lg leading-4 cursor-pointer aos-init aos-animate" data-aos="fade-right" data-aos-duration="1500" :class="isNaqd ? 'active' : 'deactivated'" @click="oylikToNaqd">Naqt to'lash</h2>
            <h2 class="deactivated text-[14px] 2xl:text-[16px] 2xl:leading-[18px] 2xl:py-[14px] 2xl:px-[12px] 2xl:w-[206px] w-[174px] px-[12px] py-[6px] rounded-lg leading-4 cursor-pointer aos-init aos-animate" data-aos="fade-left" data-aos-duration="1500" :class="isOylik ? 'active' : 'deactivated'" @click="naqtToOylik">Bo'lib to'lash</h2>
        </div>

        <div class="py-[20px] 2xl:py-[40px]">
            <div class="flex items-center justify-center gap-3 pb-[12px] 2xl:pb-[24px] 2xl:gap-[24px]">
                <div class="bg-[#FFFFFF] border-[#E0E0E0] border flex items-center justify-center flex-col 2xl:px-[25px] rounded-lg gap-4 p-[15px]  2xl:py-[25px] 2xl:w-[636px] aos-init aos-animate" data-aos="fade-up-right" data-aos-duration="1500">
                    <h1 class="bg-[#E0E0E0] rounded-full text-[24px] 2xl:text-[40px] 2xl:w-[71px] text-center text-[#1B1B35] font-medium py-[4px] px-[15px]">B</h1>
                    <p class="text-[#1B1B35] text-[22px] 2xl:text-[34px] font-semibold" v-if="isNaqd">2 900 000</p>
                    <p class="text-[#808080] text-[14px] 2xl:text-[18px] w-[140px] 2xl:w-[366px] text-center" v-if="isOylik">Boshlangich o'qish summasi 40% qolgani 90 kun ichida, o'qish davomiyligi  4 oy 20 kun</p>
                    <div class="2xl:w-[150px]">
                        <img src="../assets/car.svg" alt="car">
                    </div>
                    <button class="border-[#E0E0E0] border-[2px] px-[22px] py-[12px] 2xl:w-full rounded-lg text-[14px] text-[#1B1B35] font-medium cursor-pointer">
                        Kursni tanlash
                    </button>
                </div>
                <div class="bg-[#FFFFFF] border-[#E0E0E0] border flex items-center justify-center flex-col 2xl:px-[25px] rounded-lg gap-4 p-[15px]  2xl:py-[25px] 2xl:w-[636px]  aos-init aos-animate" data-aos="fade-up-left" data-aos-duration="1500">
                    <h1 class="bg-[#E0E0E0] rounded-full text-[24px] 2xl:text-[40px] 2xl:w-[71px] text-center text-[#1B1B35] font-medium py-[4px] 2xl:px-[5px] px-[6px]">BC</h1>
                    <p class="text-[#1B1B35] text-[22px] 2xl:text-[34px] font-semibold" v-if="isNaqd">3 500 000</p>
                    <p class="text-[#808080] text-[14px] 2xl:text-[18px] w-[140px] 2xl:mb-[26px] mb-[42px] 2xl:w-[366px] text-center" v-if="isOylik">Boshlangich o'qish summasi 1 000 000, o'qish davomiyligi 6 oy </p>
                    <div class="2xl:w-[150px]">
                        <img src="../assets/car.svg" alt="car">
                    </div>
                    <button class="border-[#E0E0E0] border-[2px] px-[22px] py-[12px] 2xl:w-full rounded-lg text-[14px] text-[#1B1B35] font-medium cursor-pointer">
                        Kursni tanlash
                    </button>
                </div>
            </div>
            <div class=" 2xl:flex hidden items-center justify-center gap-3 pb-[12px] 2xl:pb-[24px] 2xl:gap-[24px]">
                <div class="bg-[#FFFFFF] border-[#E0E0E0] border flex items-center justify-center flex-col 2xl:px-[25px] rounded-lg gap-4 p-[15px]  2xl:py-[25px] 2xl:w-[416px] aos-init aos-animate" data-aos="fade-up-right" data-aos-duration="1500">
                    <h1 class="bg-[#E0E0E0] rounded-full text-[24px] 2xl:text-[40px] 2xl:w-[71px] text-center text-[#1B1B35] font-medium py-[4px] px-[13px]">C</h1>
                    <p class="text-[#1B1B35] text-[22px] 2xl:text-[34px] font-semibold" v-if="isNaqd">1 300 000</p>
                    <p class="text-[#808080] text-[14px] 2xl:text-[18px]  w-[140px] 2xl:w-[366px] text-center 2xl:mb-[28px]" v-if="isOylik">50% dan 2 oy, o'qish davomiyligi 2 oy</p>
                    <div class="2xl:w-[166px] w-[98px]">
                        <img src="../assets/car2.svg" alt="car">
                    </div>
                    <button class="border-[#E0E0E0] border-[2px] px-[22px] py-[12px] 2xl:w-full rounded-lg text-[14px] text-[#1B1B35] font-medium cursor-pointer">
                        Kursni tanlash
                    </button>
                </div>
                <div class="bg-[#FFFFFF] border-[#E0E0E0] border flex items-center justify-center flex-col 2xl:px-[25px] rounded-lg gap-4 p-[15px]  2xl:py-[25px] 2xl:w-[416px] aos-init aos-animate" data-aos="fade-up" data-aos-duration="1500">
                    <h1 class="bg-[#E0E0E0] rounded-full text-[24px] 2xl:text-[40px] 2xl:w-[71px] text-center text-[#1B1B35] font-medium py-[4px] px-[13px]">D</h1>
                    <p class="text-[#1B1B35] text-[22px] 2xl:text-[34px] font-semibold" v-if="isNaqd">3 100 000</p>
                    <p class="text-[#808080] text-[14px] 2xl:text-[18px] w-[140px] 2xl:w-[366px] text-center 2xl:mb-[2.5px]" v-if="isOylik">Boshlangich o'qish summasi 45%,  o'qish davomiyligi 3 oy</p>
                    <div class="2xl:w-[129px] w-[74px]">
                        <img src="../assets/car3.svg" alt="car">
                    </div>
                    <button class="border-[#E0E0E0] border-[2px] px-[22px] py-[12px] 2xl:w-full rounded-lg text-[14px] text-[#1B1B35] font-medium cursor-pointer">
                        Kursni tanlash
                    </button>
                </div>
                <div class="bg-[#FFFFFF] border-[#E0E0E0] border flex items-center justify-center flex-col 2xl:px-[25px] rounded-lg gap-4 p-[15px]  2xl:py-[25px] 2xl:w-[416px] aos-init aos-animate" data-aos="fade-up-left" data-aos-duration="1500">
                    <h1 class="bg-[#E0E0E0] rounded-full text-[24px] 2xl:text-[40px] 2xl:w-[71px] text-center text-[#1B1B35] font-medium py-[4px] px-[13px]">E</h1>
                    <p class="text-[#1B1B35] text-[22px] 2xl:text-[34px] font-semibold" v-if="isNaqd">1 500 000</p>
                    <p class="text-[#808080] text-[14px] 2xl:text-[18px] w-[140px] 2xl:w-[366px] text-center" v-if="isOylik">Boshlangich o'qish summasi  50% 2 oy, o'qish davomiyligi 2 oy</p>
                    <div class="2xl:w-[252px] w-[142px]">
                        <img src="../assets/car4.svg" alt="car">
                    </div>
                    <button class="border-[#E0E0E0] border-[2px] px-[22px] py-[12px] 2xl:w-full rounded-lg text-[14px] text-[#1B1B35] font-medium cursor-pointer">
                        Kursni tanlash
                    </button>
                </div>
            </div>
            <div class=" 2xl:hidden flex items-center justify-center gap-3 pb-[12px] 2xl:pb-[24px] 2xl:gap-[24px]">
                <div class="bg-[#FFFFFF] border-[#E0E0E0] border flex items-center justify-center flex-col 2xl:px-[25px] rounded-lg gap-4 p-[15px]  2xl:py-[25px] 2xl:w-[416px] aos-init aos-animate" data-aos="fade-up-right" data-aos-duration="1500">
                    <h1 class="bg-[#E0E0E0] rounded-full text-[24px] 2xl:text-[40px] 2xl:w-[71px] text-center text-[#1B1B35] font-medium py-[4px] px-[13px]">C</h1>
                    <p class="text-[#1B1B35] text-[22px] 2xl:text-[34px] font-semibold" v-if="isNaqd">1 300 000</p>
                    <p class="text-[#808080] text-[14px] 2xl:text-[18px]  w-[140px] 2xl:w-[366px] text-center 2xl:mb-[28px] mb-[20px]" v-if="isOylik">50% dan 2 oy, o'qish davomiyligi 2 oy</p>
                    <div class="2xl:w-[166px] w-[98px]">
                        <img src="../assets/car2.svg" alt="car">
                    </div>
                    <button class="border-[#E0E0E0] border-[2px] px-[22px] py-[12px] 2xl:w-full rounded-lg text-[14px] text-[#1B1B35] font-medium cursor-pointer">
                        Kursni tanlash
                    </button>
                </div>
                <div class="bg-[#FFFFFF] border-[#E0E0E0] border flex items-center justify-center flex-col 2xl:px-[25px] rounded-lg gap-4 p-[15px]  2xl:py-[25px] 2xl:w-[416px] aos-init aos-animate" data-aos="fade-up-left" data-aos-duration="1500">
                    <h1 class="bg-[#E0E0E0] rounded-full text-[24px] 2xl:text-[40px] 2xl:w-[71px] text-center text-[#1B1B35] font-medium py-[4px] px-[13px]">D</h1>
                    <p class="text-[#1B1B35] text-[22px] 2xl:text-[34px] font-semibold" v-if="isNaqd">3 100 000</p>
                    <p class="text-[#808080] text-[14px] 2xl:text-[18px] w-[140px] 2xl:w-[366px] text-center 2xl:mb-[2.5px]" v-if="isOylik">Boshlangich o'qish summasi 45%,  o'qish davomiyligi 3 oy</p>
                    <div class="2xl:w-[129px] w-[74px]">
                        <img src="../assets/car3.svg" alt="car">
                    </div>
                    <button class="border-[#E0E0E0] border-[2px] px-[22px] py-[12px] 2xl:w-full rounded-lg text-[14px] text-[#1B1B35] font-medium cursor-pointer">
                        Kursni tanlash
                    </button>
                </div>
            </div>
            <div class=" 2xl:hidden flex items-center justify-center gap-3 pb-[12px] 2xl:pb-[24px] 2xl:gap-[24px]">
                <div class="bg-[#FFFFFF] border-[#E0E0E0] border flex items-center justify-center flex-col 2xl:px-[25px] rounded-lg gap-4 p-[15px]  2xl:py-[25px] w-[353px] 2xl:w-[416px] aos-init aos-animate" data-aos="fade-up" data-aos-duration="1500">
                    <h1 class="bg-[#E0E0E0] rounded-full text-[24px] 2xl:text-[40px] 2xl:w-[71px] text-center text-[#1B1B35] font-medium py-[4px] px-[13px]">E</h1>
                    <p class="text-[#1B1B35] text-[22px] 2xl:text-[34px] font-semibold" v-if="isNaqd">1 500 000</p>
                    <p class="text-[#808080] text-[14px] 2xl:text-[18px] w-[140px] 2xl:w-[366px] text-center" v-if="isOylik">Boshlangich o'qish summasi  50% 2 oy, o'qish davomiyligi 2 oy</p>
                    <div class="2xl:w-[252px] w-[142px]">
                        <img src="../assets/car4.svg" alt="car">
                    </div>
                    <button class="border-[#E0E0E0] border-[2px] px-[22px] py-[12px] w-full rounded-lg text-[14px] text-[#1B1B35] font-medium cursor-pointer">
                        Kursni tanlash
                    </button>
                </div>
            </div>
        </div>

        <button class="bg-[#407BFF] flex items-center justify-center rounded-[50px] w-[353px] py-[14px] 2xl:w-[400px] 2xl:py-[15px] mx-auto aos-init aos-animate" data-aos="zoom-in-up" data-aos-duration="1500">
            <p class="text-white font-medium text-[16px] 2xl:text-[20px] text-center">Ariza qoldirish</p>
        </button>
    </div>
</template>
<script>
export default {
    data() {
        return{
            isNaqd: true,
            isOylik: false,
        }
    },
    methods: {
        naqtToOylik() {
            if((this.isNaqd = true)) {
                this.isNaqd = false;
                this.isOylik = true;
            }
        },
        oylikToNaqd() {
            if((this.isOylik = true)) {
                this.isNaqd = true,
                this.isOylik = false
            }
        }
    },
}
</script>
<style scoped>
    .active{
        background: #ffffff;
        box-shadow: 0px 3px 1px 0px rgba(0, 0, 0, 0.04),
        0px 3px 8px 0px rgba(0, 0, 0, 0.12);
        border: 0.5px solid rgba(40, 41, 49, 0.04);
        text-align: center;
        color:  #407bff;
        font-weight: 600;
        transition: 0.3s;
    }
    .deactivated {
        text-align: center;
        transition: 0.3s;
        font-weight: 400;
    }
</style>