<template>
    <div>
        
        <NavbarHead />
        <HeaderDesign />
        <HeaderCard />
        <CarouselSection />
        <SectionTemplate />
        <CardSection />


    </div>
</template>
<script>
import HeaderDesign from '@/components/CopyUi/HeaderDesign.vue';
import NavbarHead from '@/components/CopyUi/NavbarHead.vue';
import HeaderCard from '@/components/CopyUi/HeaderCard.vue';
import CarouselSection from '@/components/CopyUi/CarouselSection.vue';
import SectionTemplate from '@/components/CopyUi/SectionTemplate.vue';
import CardSection from '@/components/CopyUi/CardSection.vue';

import { defineComponent } from 'vue';

export default defineComponent ({
    components: {
        NavbarHead,
        HeaderDesign,
        HeaderCard,
        CarouselSection,
        SectionTemplate,
        CardSection,
    }
})
</script>
<style>
    
</style>