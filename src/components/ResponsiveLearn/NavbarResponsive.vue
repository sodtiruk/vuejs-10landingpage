<template>
    <div class="grid">
        <div class="box"></div> 
        <div class="box"></div> 
        <div class="box"></div> 
        <div class="box"></div> 
        <div class="box"></div> 
        <div class="box"></div> 
        <div class="box"></div> 
    </div>
</template>
<script>
import { defineComponent } from 'vue';

export default defineComponent({
    components: {

    }   
})
</script>
<style scoped>
    
.grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
}    

.box {
    background-color: blue;
    border: 1px solid red;
    padding: 1rem;
}

@media screen and (max-width: 600px){

    .grid {
        grid-template-columns: repeat(2, 1fr);
    }

    .box {
        background-color: blueviolet;
    }


}


</style>