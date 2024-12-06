<template>
    <div class="section">
        <div class="container">
            <div class="content">
                <div class="left-content">
                    <h5>Template</h5>
                    <h1>Exceptional templates for a quick start</h1>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Minus, quaerat ratione similique minima
                        obcaecati amet. Praesentium veniam quod molestiae, corporis eum, dignissimos officia mollitia
                        laboriosam a iste dolores, eligendi nemo!</p>
                    <button>Explore Templates</button>
                </div>
                <div class="right-content">
                    <img src="https://i.pinimg.com/originals/d0/40/91/d040918a7d9190d1a66d755014e44c7d.gif" alt="">
                </div>
            </div>
        </div>
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

.section {
    margin-top: 5rem;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    font-weight: lighter;
}

.container {
    max-width: 1040px;
    margin: 0 auto;
}

.content {
    display: flex;
    align-items: center;
    justify-content: center;
}

.left-content {
    width: 40%;
    margin-right: 3rem;
}

.left-content h5 {
    font-size: 18px; 
    background: linear-gradient(90deg, rgba(56,8,138,1) 0%, rgba(65,9,121,1) 26%, rgba(63,14,125,1) 37%, rgba(56,36,139,1) 44%, rgba(45,71,162,1) 65%, rgba(25,134,203,1) 80%, rgba(0,212,255,1) 100%);
    -webkit-background-clip: text;
    background-clip: text;
    -webkit-text-fill-color: transparent;
}

.left-content h1 {
    font-size: 30px;
    font-weight: bold;
}

.left-content p {
    font-size: 18px;
    color: gray;
}

.left-content button {
    margin-top: 1rem;
    background: none;
    border: 1px solid violet;
    border-radius: 22px;
    color: violet;
    padding: 1rem;
    width: 16rem;
    font-size: 18px;
    font-weight: bold;
}


.left-content button:hover { 
    background-color: violet; 
    color: white;
}

</style>