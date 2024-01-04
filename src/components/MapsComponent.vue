<template >
    <div
        @click="$emit('toogleOpen' , index)"
        :class="open ? 'faq open' : 'faq'"
    >
        <p>fillial</p>
        <div class="answer text-[16px]   font-bold 2xl:text-[23px] 2xl:leading-[59px] aos-init aos-animate" data-aos="fade-up-right"  data-aos-duration="1500">
            <p class="max-w-[270px] 2xl:max-w-[900px] aos-init aos-animate">{{ fil.manzil }}</p>
            <p class="max-w-[270px] 2xl:max-w-[900px] aos-init aos-animate">{{ fil.tel }}</p>
        </div>  
    </div>
</template>
<script>
export default {
    name: 'MapsComponent',
    props: ['fil', 'index' , 'open']
}
</script>
<style lang="">
    
</style>