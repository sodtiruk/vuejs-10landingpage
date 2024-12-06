<template>
    <div class="main">
        <div class="container">
            <div class="about-us">
                <div class="links">
                    <p>Links</p>
                    <ul>
                        <li>Components</li>
                        <li>Templates</li>
                        <li>Pricing</li>
                        <li>Contact</li>
                        <li>Sign in</li>
                        <li>Sign up</li>
                    </ul>
                </div>
                <div class="legal">
                    <p>Legal</p>
                    <ul>
                        <li>Privacy policy</li>
                        <li>Terms of service</li>
                    </ul>
                </div>
                <div class="other">
                    <p>Other</p>
                    <div class="boxs">
                        <div class="box">
                            <img src="https://i.pinimg.com/736x/a3/54/f7/a354f70453e018d1fb1484f3a4620cc1.jpg" alt="">
                            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Necessitatibus, dolore.</p>
                        </div>
                        <div class="box">
                            <img src="https://i.pinimg.com/736x/5f/b7/f0/5fb7f0212e170154dc89ae9507945edf.jpg" alt="">
                            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Necessitatibus, dolore.</p>
                        </div>
                        <div class="box">
                            <img src="https://i.pinimg.com/736x/74/0f/f8/740ff8868aab254c22dd381e0f6f1992.jpg" alt="">
                            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Necessitatibus, dolore.</p>
                        </div>
                        <div class="box">
                            <img src="https://i.pinimg.com/736x/96/c9/f7/96c9f72372d69070c4638fb05c1e2531.jpg" alt="">
                            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Necessitatibus, dolore.</p>
                        </div>
                    </div>
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

* {
    list-style: none;
}

.main {
    margin-top: 5rem;
}

.container {
    max-width: 1040px;
    margin: 0 auto;
}

.about-us {
    display: flex;
    justify-content: space-between;
}

.about-us .links {
    font-size: 16px;
}

.about-us .links p{
    font-weight: 600;
    margin-bottom: 5px;
}

.about-us .links ul {
    font-weight: 350;
}

.about-us .legal {
    font-size: 16px;
}

.about-us .legal p{
    font-weight: 600;
    margin-bottom: 5px;
}

.about-us .legal ul{
    font-weight: 350;
}

.about-us .other p:first-child{
    font-weight: 600;
    margin-bottom: 12px;
}

.about-us .other {
    margin-bottom: 5px;
}

.about-us .other .boxs .box {
    display: flex;
    background: #f4f2f2;
    padding: 12px 16px;
    border-radius: 18px;
    width: 350px;
    margin-bottom: 8px;
    align-items: center;
 }

.about-us .other .boxs .box img {
    width: 50px;
    height: 50px;
    border-radius: 14px;
    margin-right: 10px;
}

</style>