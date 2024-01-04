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
                                <div class="">
                                    <div class="rounded-t-[8px] border-b-[1px] border-[#455674] py-[10px] px-[15px] bg-[#323E55]">
                                        <p class="font-medium text-[14px] text-white">B kategoriyasi uchun boshlang'ich to'lov 1 160 000 so'mdan 0% nasiya </p>
                                    </div>
                                    <div class="rounded-b-[8px] py-[10px] px-[15px] bg-[#323E55]">
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



        <div class=" 2xl:w-[1259px] pb-[137px] mx-auto 2xl:block hidden">
            <div class="flex items-start justify-between mb-[62px] mt-[20px]">
                <a href="#">
                    <img src="../assets/logo.svg" alt="logo">
                </a>
                <div class="bg-[#444444] border-[1px] border-[#515359] py-[15px] px-[30px] rounded-[50px] gap-[40px] flex mx-auto ">
                    <a class="text-white text-[18px] font-medium hover:text-[#407BFF]" href="#narxlar">Narxlar</a>
                    <a class="text-white text-[18px] font-medium hover:text-[#407BFF]" href="#filiallar">Filiallar</a>
                </div>
            </div>

            <div>
                <div class="mb-[70px]">
                    <div class="mb-[50px]">
                        <p class="mb-[20px] font-black text-[50px] w-[746px] uppercase text-white">Hech qanday qo'rquv va stresslarsiz Mashina haydashni o'rganing!</p>
                        <div class="flex items-center gap-[10px]">
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
            <div class="header_modal bg-white 2xl:w-[450px] w-[353px]  mx-auto  mx-auto 2xl:mt-[10%] mt-[234px] p-[20px] rounded-[12px] 2xl:py-[40px] 2xl:px-[30px] relative">
                <button v-on:click="isOpen = !isOpen" class="absolute top-[-30px] right-0">
                    <img src="../assets/plus.svg" alt="plus">
                </button>

                <h1 class="text-center 2xl:text-[24px] text-[20px] font-semibold mb-[3px]">Telefon raqamingizni qoldiring</h1>
                <p class="text-center text-[#BABABA] 2xl:text-[18px] text-[16px] mb-[20px]">Biz siz bilan albatta bog'lanamiz</p>           
                <form @submit.prevent="submitForm">
                    <div class="input-container border-b-[1px] border-[#E0E0E0] w-full mb-[40px]">
                        <input class="" type="text" id="name" name="name" v-model="name" required>
                        <label for="name">Ism</label>
                    </div>
                    <div class="input-container border-b-[1px] border-[#E0E0E0] w-full mb-[40px]">
                        <input class=" " type="tel" id="tel" name="tel" v-model="tel" required>
                        <label for="tel">Raqamingiz</label> 
                    </div>
                    <button type="submit" class="w-full py-[14px] bg-[#407BFF] rounded-[50px] 2xl:rounded-[52px] 2xl:py-[15px]">
                        <p class="text-white 2xl:text-[20px] font-medium text-center text-[16px]">Ariza qoldirish</p>
                    </button>
                </form>
            </div>
        </div>

        <div class="absolute bottom-0 right-0 w-[448px] 2xl:block hidden " >
            <div class="bg-[#4C4C4C]  py-[10px] px-[20px] rounded-l-[16px] rounded-t-[16px] absolute bottom-[301px] right-[58px]">
                <p class="text-[#D8E1FF] text-[20px] font-medium text-center">Xonalarimiz eshiklari siz uchun ochiq</p>
            </div>
            <img src="../assets/carvector.png" alt="">
        </div>

        <button @click="scrollToTop" class="fixed bottom-[5%] right-[20px] 2xl:w-[60px] w-[40px] h-[40px] 2xl:h-[60px] p-[12px] bg-[#407BFF] rounded-[12px]">
            <img  src="../assets/arrow2.svg" alt="arrow">
        </button>
    </div>
</template>
<script>
import axios from 'axios'
import Swal from 'sweetalert2'
export default {
    data : () => {
        return {
            isOpen: false,
            name: "",
            tel: "",
            validationErrors: {},
            isSubmitting: false,

            telegramBotToken: '6759172233:AAGRTTni5aSpI5flaMzPhlJMZUvq_BGqYeE',
            chatId: 660182754,
        }
    },
    
    methods: {
        scrollToTop() {
            window.scrollTo({
                top: 0,
                behavior: 'smooth'
            })
        },

        submitForm() {
            const fullMessage = `Full name: ${this.name}
                                 \n Tel: ${this.tel}
                                 `
            axios.post(`https://api.telegram.org/bot${this.telegramBotToken}/sendMessage?chat_id=${this.chatId}&text=${fullMessage}`, {
                name: this.name,
                tel: this.tel,
                chatId: this.chatId,
                telegramBotToken: this.telegramBotToken
            })
            .then(response => {
                console.log(response.data);
                Swal.fire({
                    title: "Arizangiz muvafaqqiyatli yuborildi",
                    icon: "success",
                    iconColor: '#407BFF',
                    timer: 2000,
                    showConfirmButton: false,
                    showClass: {
                        popup: `
                            animate__animated
                            animate__fadeInUp
                            animate__faster
                        `
                    },
                    hideClass:{
                        popup: `
                            animate__animated
                            animate__fadeOutDown
                            animate__faster
                        `
                    }
                })
            })
            .catch(error => {
                console.log(error);
                Swal.fire({
                    title: "Arizangiz yuborilmadi",
                    icon: "error",
                    showClass: {
                        popup: `
                            animate__animated
                            animate__fadeInUp
                            animate__faster
                        `
                    },
                    hideClass:{
                        popup: `
                            animate__animated
                            animate__fadeOutDown
                            animate__faster
                        `
                    },
                    showConfirmButton: false
                })
            })
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
.input-container {
      position: relative;
    }

    input {
      width: 100%;
      padding: 10px;
    }

    label {
      position: absolute;
      top: 50%;
      left: 10px;
      transform: translateY(-50%);
      pointer-events: none;
      transition: 0.3s;
    }

    input:focus + label,
    input:valid + label {
      top: 5px;
      font-size: 12px;
      color: #407BFF;
    }
input{
    outline: none;
}
    .header_box{
        background-image: url('../assets/header-bg.png') , url('../assets/blurcolor.png');
        background-repeat: no-repeat;
        background-position: top center;
        background-size: 100% , cover;
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
            background-position-x: 100% ;
            background-position-y: -15px;
        }
    }
</style>