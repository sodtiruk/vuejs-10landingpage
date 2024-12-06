<template>
    <div class="section">
        <n-carousel autoplay>
            <img class="carousel-img" src="https://naive-ui.oss-cn-beijing.aliyuncs.com/carousel-img/carousel1.jpeg">
            <img class="carousel-img" src="https://naive-ui.oss-cn-beijing.aliyuncs.com/carousel-img/carousel2.jpeg">
            <img class="carousel-img" src="https://naive-ui.oss-cn-beijing.aliyuncs.com/carousel-img/carousel3.jpeg">
            <img class="carousel-img" src="https://naive-ui.oss-cn-beijing.aliyuncs.com/carousel-img/carousel4.jpeg">
        </n-carousel>
    </div>
</template>
<script>
import { NCarousel } from 'naive-ui';
import { defineComponent } from 'vue';

export default defineComponent({
    components: {
        NCarousel,

    }    
})
</script>

<style scoped>

.section {
    margin-top: 3rem;
}
    
.carousel-img {
    width: 100%;
    height: 500px;
    object-fit: contain;
}

</style>