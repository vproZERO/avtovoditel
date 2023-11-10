<template>
    <div class="container">
        <div class="2xl:block hidden py-[150px]">
            <h1 class="uppercase text-center text-[40px] font-bold mb-[70px] aos-init aos-animate" data-aos="fade-up" data-aos-duration="1500">TA'LIM BOSQICHLARI</h1>
            <div class="flex items-center justify-around aos-init aos-animate" data-aos-duration="1500" data-aos="fade-up">
                <div>
                    <div class="mb-[15px] w-[70px] mx-auto">
                        <img src="../assets/t1.svg" alt="img">
                    </div>
                    <div class="mb-[15px] w-[45px] mx-auto  ">
                        <img class=" p-[10px] rounded-full bg-[#E0E0E0] animated-img" src="../assets/d1.svg" alt="img">
                    </div>
                    <h2 class="text-[24px] text-center font-normal text-[#1B1B35]">Nazariy kurs</h2>
                </div>

                <div class="animated-text text-[20px] text-[#E0E0E0] w-[250px]">
                    ---------------------------
                </div>

                <div>
                    <div class="mb-[15px] w-[70px] mx-auto">
                        <img src="../assets/t2.svg" alt="img">
                    </div>
                    <div class="mb-[15px] w-[45px] mx-auto ">
                        <img class=" p-[10px] rounded-full bg-[#E0E0E0] animated-img2" src="../assets/d1.svg" alt="img">
                    </div>
                    <h2 class="text-[24px] text-center font-normal text-[#1B1B35]">Amaliy kurs</h2>
                </div>

                <div class="animated-text2 text-[20px] text-[#E0E0E0] w-[250px]">
                    ---------------------------
                </div>

                <div>
                    <div class="mb-[15px] w-[70px] mx-auto">
                        <img src="../assets/t3.svg" alt="img">
                    </div>
                    <div class="mb-[15px] w-[45px] mx-auto">
                        <img class=" p-[10px] rounded-full bg-[#E0E0E0] animated-img3" src="../assets/d1.svg" alt="img">
                    </div>
                    <h2 class="text-[24px] text-center font-normal text-[#1B1B35]">Ichki imtihon</h2>
                </div>

                <div class="animated-text3 text-[20px] text-[#E0E0E0] w-[250px]">
                    ---------------------------
                </div>

                <div>
                    <div class="mb-[15px] w-[70px] mx-auto">
                        <img src="../assets/t4.svg" alt="img">
                    </div>
                    <div class="mb-[15px] w-[45px] mx-auto  ">
                        <img class=" p-[10px] rounded-full bg-[#E0E0E0] animated-img4" src="../assets/d2.svg" alt="img">
                    </div>
                    <h2 class="text-[24px] text-center font-normal text-[#1B1B35]">YHXX imtihoni</h2>
                </div>
            </div>
        </div>


        <div class="2xl:hidden block py-[50px] ">
            <h1 class="text-center font-bold text-[24px] text-[#1B1B35] mb-[30px] aos-init aos-animate" data-aos-duration="1500" data-aos="fade-up">TA'LIM BOSQICHLARI</h1>
            <div class="aos-init aos-animate" data-aos="fade-up" data-aos-duration="1500">
                <div class="flex items-center justify-around mb-[50px] " >
                    <div>
                        <div class="mb-[5px] w-[50px] mx-auto">
                            <img src="../assets/t1.svg" alt="img">
                        </div>
                        <div class="mb-[5px] w-[35px] mx-auto ">
                            <img class="p-[8px] animated-img rounded-full" src="../assets/d1.svg" alt="img">
                        </div>
                        <p class="text-[18px]  font-normal text-[#1B1B35]">Nazariy kurs</p>
                    </div>
                    <div class="animated-text text-[#E0E0E0] text-[20px] max-w-[150px]">
                        ----------
                    </div>

                    <div>
                        <div class="mb-[5px] w-[50px] mx-auto">
                            <img src="../assets/t2.svg" alt="img">
                        </div>
                        <div class="mb-[5px] w-[35px] mx-auto  rotate-[90deg]">
                            <img class="p-[8px] animated-img2 rounded-full" src="../assets/d1.svg" alt="img">
                        </div>
                        <h2 class="text-[18px] text-center font-normal text-[#1B1B35]">Amaliy kurs</h2>
                    </div>
                </div>

                <div class="animated-text2 text-[20px] max-w-[150px] max-h-[30px] mb-[50px] rotate-[90deg] ml-[71%] ">
                    ----------
                </div>

                <div class="flex items-center justify-around ">
                    <div>
                        <div class="mb-[5px] w-[50px] mx-auto">
                            <img src="../assets/t4.svg" alt="img">
                        </div>
                        <div class="mb-[5px] w-[35px] mx-auto  rotate-[180deg]">
                            <img class="p-[8px] animated-img4 rounded-full " src="../assets/d1.svg" alt="img">
                        </div>
                        <p class="text-[18px]  font-normal text-[#1B1B35]">YHXX imtihoni</p>
                    </div>
                    <div class="animated-text3 text-[20px] max-w-[150px]">
                        ----------
                    </div>

                    <div>
                        <div class="mb-[5px] w-[50px] mx-auto">
                            <img src="../assets/t3.svg" alt="img">
                        </div>
                        <div class="mb-[5px] w-[35px] mx-auto ">
                            <img class="p-[8px] animated-img3 rounded-full " src="../assets/d2.svg" alt="img">
                        </div>
                        <h2 class="text-[18px] text-center font-normal text-[#1B1B35]">Ichki imtihon</h2>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
@keyframes colorChange {
  0% {
    color: #E0E0E0;
  }
  50%{
    color: #407BFF;

  }
  100% {
    color: #407BFF;
  }
}
@keyframes colorChangeBg {
  0% {
    background: #E0E0E0;
  }
  50%{
    background: #407BFF;

  }
  100% {
    background: #407BFF;
  }
}
@keyframes colorChangeBg2 {
  0% {
    background: #E0E0E0;
  }
  50%{
    background: #407BFF;

  }
  100% {
    background: #407BFF;
  }
}

    .animated-text {
    animation: colorChange 15s ;
    background: linear-gradient(to right, #E0E0E0, #407BFF);
    background-clip: text;
    -webkit-background-clip: text;
    color: transparent;
    display: inline-block;
    animation-fill-mode: forwards;
}
.animated-text2 {
    animation: colorChange 25s ;
    background: linear-gradient(to right, #E0E0E0, #407BFF);
    background-clip: text;
    -webkit-background-clip: text;
    color: transparent;
    display: inline-block;
    animation-fill-mode: forwards;
}
.animated-text3 {
    animation: colorChange 35s ;
    background: linear-gradient(to right, #E0E0E0, #407BFF);
    background-clip: text;
    -webkit-background-clip: text;
    color: transparent;
    display: inline-block;
    animation-fill-mode: forwards;
}
.animated-img {
  animation: colorChangeBg 4s ;
  background: linear-gradient(to right, #E0E0E0, #407BFF);
  background-clip: text;
  -webkit-background-clip: text;
  color: transparent;
  display: inline-block;
  animation-fill-mode: forwards;
  margin: 0 auto;
}
.animated-img2 {
  animation: colorChangeBg2 15s ;
  background: linear-gradient(to right, #E0E0E0, #407BFF);
  background-clip: text;
  -webkit-background-clip: text;
  color: transparent;
  display: inline-block;
  animation-fill-mode: forwards;
  margin: 0 auto;
}
.animated-img3 {
  animation: colorChangeBg2 25s ;
  background: linear-gradient(to right, #E0E0E0, #407BFF);
  background-clip: text;
  -webkit-background-clip: text;
  color: transparent;
  display: inline-block;
  animation-fill-mode: forwards;
  margin: 0 auto;
}
.animated-img4 {
  animation: colorChangeBg2 45s ;
  background: linear-gradient(to right, #E0E0E0, #407BFF);
  background-clip: text;
  -webkit-background-clip: text;
  color: transparent;
  display: inline-block;
  animation-fill-mode: forwards;
  margin: 0 auto;
}


</style>