<template>
    <section>
        <div class="container">
            <div class="card-user">
                <p class="detail">Lorem ipsum dolor sit amet consectetur adipisicing elit. Culpa, animi laboriosam sunt ipsa voluptatum blanditiis. Est praesentium quasi non quaerat.</p>
                <div class="logo-person">
                    <img src="https://img.freepik.com/free-photo/portrait-upset-american-black-person_23-2148749581.jpg" alt="">
                </div>
                <h3>Peter Mick</h3>
                <p class="position">Founder of Copylime and TweetAI</p>
            </div>
            <div class="box">
                <h3>Pricing</h3>
                <h1>Gain A Competitive Edge With Better UI!</h1>
                <p>Limited time offer: Join our growing community of 950+ satisfied users</p>
            </div>
            <div class="card-sale">
                <div class="left-content">
                    <div class="detail">
                        <div class="split">
                            <AlertOn24Filled style="width: 20px; height: 20px; margin-top: 2px; color: #22A45F;"/>
                            <div class="explain-detail">Lorem ipsum dolor sit amet consectetur adipisicing elit. Minima, excepturi.</div> 
                        </div>
                        <div class="split">
                            <AlertOn24Filled style="width: 20px; height: 20px; margin-top: 2px; color: #22A45F;"/>
                            <div class="explain-detail">Lorem ipsum dolor sit amet consectetur adipisicing elit. Minima, excepturi.</div> 
                        </div>
                        <div class="split">
                            <AlertOn24Filled style="width: 20px; height: 20px; margin-top: 2px; color: #22A45F;"/>
                            <div class="explain-detail">Lorem ipsum dolor sit amet consectetur adipisicing elit. Minima, excepturi.</div> 
                        </div>
                        <div class="split">
                            <AlertOn24Filled style="width: 20px; height: 20px; margin-top: 2px; color: #22A45F;"/>
                            <div class="explain-detail">Lorem ipsum dolor sit amet consectetur adipisicing elit. Minima, excepturi.</div> 
                        </div>
                        <div class="split">
                            <AlertOn24Filled style="width: 20px; height: 20px; margin-top: 2px; color: #22A45F;"/>
                            <div class="explain-detail">Lorem ipsum dolor sit amet consectetur adipisicing elit. Minima, excepturi.</div> 
                        </div>
                    </div>
                </div>
                <div class="right-content">
                    <div class="cards">
                        <div class="card">
                            <div class="left">
                                <button>Limited time offer!</button>
                                <h2>Forever full access</h2>
                                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Natus, odit!</p> 
                            </div>
                            <div class="right">
                                <div class="box-right">
                                    <h3 class="price">$59</h3>
                                    <p>Save 76%</p>
                                    <p>One-time payment, access forever!</p>
                                    <button>Get access forever</button>
                                </div>
                            </div>
                        </div>
                        <div class="card">
                            <div class="left">
                                <button>Limited time offer!</button>
                                <h2>Forever full access</h2>
                                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Natus, odit!</p> 
                            </div>
                            <div class="right">
                                <div class="box-right">
                                    <h3 class="price">$59</h3>
                                    <p>Save 76%</p>
                                    <p>One-time payment, access forever!</p>
                                    <button>Get access forever</button>
                                </div>
                            </div>
                        </div>
                        <div class="card">
                            <div class="left">
                                <button>Limited time offer!</button>
                                <h2>Forever full access</h2>
                                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Natus, odit!</p> 
                            </div>
                            <div class="right">
                                <div class="box-right">
                                    <h3 class="price">$59</h3>
                                    <p>Save 76%</p>
                                    <p>One-time payment, access forever!</p>
                                    <button>Get access forever</button>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>            
        </div>
    </section>
</template>
<script>
import { AlertOn24Filled } from '@vicons/fluent';
import { defineComponent } from 'vue';

export default defineComponent({
    components: {
        AlertOn24Filled,
    }   
})
</script>
<style scoped>


section {
    margin-top: 8rem;
}

.container {
    max-width: 1040px;
    margin: 0 auto;
}

.card-user {
    width: 60%;    
    margin: 0 auto;
    font-size: 22px;
    font-weight: lighter;
    font-family: Georgia, 'Times New Roman', Times, serif;
    background-color: #fbfafaed;
    padding: 3rem 3.5rem;
    border-radius: 20px;
    text-align: center;
    box-shadow: gray 2px 2px 10px;
}

.card-user .logo-person {
    width: 20%;
    margin: 0 auto;
    margin-top: 1rem;
}

.card-user .logo-person img {
    width: 80px;
    height: 80px;
    object-fit: cover;
    border-radius: 50%;
}

.card-user h3 {
    font-size: 18px;
    font-weight: lighter;
}

.card-user .position {
    font-size: 22px;
    font-weight: lighter;
    color: gray;
}

.box {
    /* margin-top: rem; */
    text-align: center;
    font-weight: lighter;
    width: 50%;
    margin: 3rem auto;
    padding: 2rem 3.5rem;
}

.box h3 {
    font-size: 22px;
    font-weight: bolder;
    color: #22A45F;
}

.box h1 {
    font-size: 2rem;
}

.card-sale {
    margin-top: -2rem;
    border: 1px solid #22A45F;
    border-radius: 20px;
    padding: 4rem 4.5rem;
    display: flex; 
    align-items: center;
    box-shadow: #22A45F 0px -2px .3rem;
}

.card-sale .left-content {
    padding: .5rem;
    width: 50%;
}

.card-sale .left-content .detail .split {
    display: flex;
    padding: .5rem;
    font-size: 16px;
}

.card-sale .right-content .cards .card{
    border: 1px solid gray;
    border-radius: 14px;
    padding: 2rem 4rem;
    margin: .7rem 0;    
    display: flex;
    align-items: center;
}

.card-sale .right-content .cards .card .left button {
    border: none;
    background: #22C55E;
    padding: 6px 8px;
    color: white; 
    border-radius: 14px;
}


.card-sale .right-content .cards .card .left h2{ 
    font-size: 24px;
}


.card-sale .right-content .cards .card .left p{ 
    color: gray;
}

.card-sale .right-content .cards .card .right .box-right{
    text-align: center;
}

.card-sale .right-content .cards .card .right .box-right h3 {
    font-size: 2.5rem;
}

.card-sale .right-content .cards .card .right .box-right button { 
    font-size: 14px;
    color: white;
    background: #22A45F;
    border: none;
    border-radius: 12px;
    padding: 8px 10px;
    width: 100%;
}

    
</style>