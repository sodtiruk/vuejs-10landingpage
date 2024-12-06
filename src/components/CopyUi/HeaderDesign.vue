<template >
    <div class="header">
        <div class="container">
            <div class="header-content">
                <div class="left-content">
                    <button class="the-most"> The most extensive and varied library of components available. </button>
                    <n-gradient-text size="110px"> Design <br> Made Easy. </n-gradient-text>
                    <div class="card">
                        <div class="card-detail">
                            <Comment16Filled style="color: green; opacity: 50%; width: 50px;"/>
                            <div class="product-detail">
                                <h5>PRODUCT HUNT</h5>
                                <h3>#2 Product of the Day</h3>
                            </div>
                        </div>
                        <div class="card-detail">
                            <Comment16Filled style="color: green; opacity: 50%; width: 50px;"/>
                            <div class="product-detail">
                                <h5>PRODUCT OF THE WEEK</h5>
                                <h3>Developer Tools</h3>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="right-content">
                    <p class="header"> Lorem ipsum dolor sit amet consectetur adipisicing elit. Blanditiis in consequatur error. Inventore deleniti quam est consequatur esse praesentium totam.</p>
                    <div class="logo-detail">
                        <AnimalCat28Filled style="width: 40px;"/>
                        <AnimalDog16Filled style="width: 40px;"/>
                        <AnimalTurtle20Filled style="width: 40px;"/>
                    </div>
                    <button class="get-full-access">
                        Get Full Access Now
                    </button>
                    <div class="ratting-detail">
                        <div class="person-logo">
                            <img src="https://www.mnp.ca/-/media/foundation/integrations/personnel/2020/12/16/13/57/personnel-image-4483.jpg?h=800&iar=0&w=600&hash=833D605FDB6AC3C2D2915F6BF8B4ADA4" alt="">
                            <img src="https://www.jordanharbinger.com/wp-content/uploads/2018/09/be-the-most-interesting-360x360.jpg" alt="">
                            <img src="https://www.georgetown.edu/wp-content/uploads/2022/02/Jkramerheadshot-scaled-e1645036825432-1050x1050-c-default.jpg" alt="">
                            <img src="https://images.pexels.com/photos/614810/pexels-photo-614810.jpeg?cs=srgb&dl=pexels-simon-robben-55958-614810.jpg&fm=jpg" alt="">
                            <img src="https://images.ladbible.com/resize?type=webp&quality=70&width=3840&fit=contain&gravity=auto&url=https://images.ladbiblegroup.com/v3/assets/bltb5d92757ac1ee045/bltc86e7943bcc0e006/6569cbef0b642304079a348b/AI-creates-what-the-average-person.png%3Fcrop%3D590%2C590%2Cx0%2Cy0" alt="">
                        </div>
                        <div class="ratting-star">
                            <div class="star">
                                <Star24Regular style="width: 20px; color: #FFA20D; margin-left: 11.8rem;"/>
                                <Star24Regular style="width: 20px; color: #FFA20D;"/>
                                <Star24Regular style="width: 20px; color: #FFA20D;"/>
                                <Star24Regular style="width: 20px; color: #FFA20D;"/>
                                <Star24Regular style="width: 20px; color: #FFA20D;"/>
                            </div>
                            <div class="message-detail">
                                <h1>965</h1>
                                <p>Startups are launching faster</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
import { AnimalCat28Filled, 
        AnimalDog16Filled, 
        AnimalTurtle20Filled, 
        Comment16Filled, 
        Star24Regular } from '@vicons/fluent';
import { NGradientText } from 'naive-ui';
import { defineComponent } from 'vue';


export default defineComponent({
    components: {
        NGradientText,
        Comment16Filled,
        AnimalTurtle20Filled,
        AnimalCat28Filled,
        AnimalDog16Filled,
        Star24Regular,
    }   
})
</script>
<style scoped>

* {
    font-weight: lighter;  
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    font-size: 14px;
}

.header {
    margin-top: 5rem;
}

.container {
    max-width: 1040px;
    margin: 0 auto;
}

.header-content {
    display: flex;
}

.left-content .the-most {
    border: 1px solid #22A45F;
    background: none;
    border-radius: 12px;
    padding: 8px;
    color: #22A45F;
}

.card {
    display: flex;
    border: 1px solid #22A45F;
    border-radius: 12px;    
    padding: 10px 12px;
}

.card .card-detail {
    display: flex;
    width: 50%;
    align-items: center;
    margin-left: 10px;
}

.card .product-detail {
    margin-left: 10px;
}

.card h5 {
    font-size: 11px;

}

.card h3 {
    font-size: 16px;
    font-weight: bold;
}

.right-content {
    margin-left: 2rem;
}

.right-content .header {
    font-size: 18px;
    margin-top: 2rem;
    color: gray;
}

.right-content .logo-detail {
    margin-top: 2rem;
}

.right-content .logo-detail * {
    margin-right: 1.2rem;
}

.right-content .get-full-access {
    border: 1px solid #22A45F;
    border-radius: 18px;
    padding: 12px 14px;
    width: 220px;
    background: none;
    margin-top: 1rem;
    font-size: 18px;
    font-weight: bold;
    color: #22A45F;
}

.ratting-detail {
    margin-top: 1rem;
    color: gray;
}

.ratting-detail .person-logo img {
    width: 50px;
    height: 50px;
    border-radius: 50%;
    border: 5px solid white;
    position: absolute;
}

.ratting-detail .person-logo img:nth-child(2){
    margin-left: 2rem;
    z-index: 1;
}

.ratting-detail .person-logo img:nth-child(3){
    margin-left: 4rem;
    z-index: 2;
}

.ratting-detail .person-logo img:nth-child(4){
    margin-left: 6rem;
    z-index: 3;
}

.ratting-detail .person-logo img:nth-child(5){
    margin-left: 8rem;
    z-index: 4;
}

.ratting-detail .message-detail {
    display: flex;
    margin-left: 12rem;
}

.ratting-detail .message-detail * {
    margin-right: 3px;
}


.ratting-detail .message-detail h1 {
    font-weight: bold;
    color: black;
}

.ratting-star .star {
    display: flex; 
}














</style>