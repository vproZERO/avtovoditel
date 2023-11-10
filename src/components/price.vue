<template>
    <div class="2xl:py-[150px] py-[50px]">
        <h1 class="text-center font-bold text-[#1B1B35] text-[24px] 2xl:text-[40px] 2xl:mb-[40px] mb-[15px]">Narxlar</h1>
        <div class="flex items-center justify-center gap-6 mt-[23px] p-[2px] bg-[#F3F3F3] rounded-lg">
            <h2 class="text-[14px] leading-4 cursor-pointer" :class="isNaqd ? 'active' : 'deactivated'" @click="oylikToNaqd">Naqt to'lash</h2>
            <h2 class="deactivated text-[14px] leading-4 cursor-pointer" :class="isOylik ? 'active' : 'deactivated'" @click="naqtToOylik">Bo'lib to'lash</h2>
        </div>

        <div class="py-[20px]">
            <div class="flex items-center justify-center gap-3 pb-[12px]">
                <div class="bg-[#FFFFFF] border-[#E0E0E0] border flex items-center justify-center flex-col rounded-lggap-4 p-[15px]">
                    <h1 class="bg-[#E0E0E0] rounded-full text-[24px] text-[#1B1B35] font-medium py-[4px] px-[15px]">B</h1>
                    <p class="text-[#1B1B35] text-[22px] font-semibold" v-if="isNaqd">2 900 000</p>
                    <p class="text-[#808080] text-[14px] w-[140px] text-center" v-if="isOylik">Boshlangich o'qish summasi 40% qolgani 90 kun ichida, o'qish davomiyligi  4 oy 20 kun</p>
                    <div>
                        <img src="../assets/car.svg" alt="car">
                    </div>
                    <button class="border-[#E0E0E0] border-[2px] px-[22px] py-[12px] rounded-lg text-[14px] text-[#1B1B35] font-medium cursor-pointer">
                        Kursni tanlash
                    </button>
                </div>
                <div class="bg-[#FFFFFF] border-[#E0E0E0] border flex items-center justify-center flex-col rounded-lggap-4 p-[15px]">
                    <h1 class="bg-[#E0E0E0] rounded-full text-[24px] text-[#1B1B35] font-medium py-[4px] px-[15px]">BC</h1>
                    <p class="text-[#1B1B35] text-[22px] font-semibold" v-if="isNaqd">2 900 000</p>
                    <p class="text-[#808080] text-[14px] w-[140px] text-center" v-if="isOylik">Boshlangich o'qish summasi 40% qolgani 90 kun ichida, o'qish davomiyligi  4 oy 20 kun</p>
                    <div>
                        <img src="../assets/car.svg" alt="car">
                    </div>
                    <button class="border-[#E0E0E0] border-[2px] px-[22px] py-[12px] rounded-lg text-[14px] text-[#1B1B35] font-medium cursor-pointer">
                        Kursni tanlash
                    </button>
                </div>
            </div>
        </div>
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
        padding: 6px 12px;
        box-shadow: 0px 3px 1px 0px rgba(0, 0, 0, 0.04),
        0px 3px 8px 0px rgba(0, 0, 0, 0.12);
        border: 0.5px solid rgba(40, 41, 49, 0.04);
        border-radius: 6px;
        width: 150px;
        text-align: center;
        color:  #407bff;
        font-weight: 600;
        transition: 0.3s;
    }
    .deactivated {
        text-align: center;
        padding: 6px 12px;
        width: 150px;
        transition: 0.3s;
    }
</style>