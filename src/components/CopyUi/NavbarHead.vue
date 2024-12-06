<template>
    <nav>
        <div class="left-content">
            <img src="https://logowik.com/content/uploads/images/free-icon670.logowik.com.webp" alt="">
            <div class="name-logo">Copy UI</div>
        </div>
        <div class="right-content">
            <div class="content">
                <ul>
                    <li>Pricing</li>
                    <li>Components</li>
                    <li>Templates</li>
                    <li>Contact</li>
                </ul>
            </div>
            <div class="split-content">
                |
            </div>
            <div class="content-button">
                <button class="signin">Sign in</button>
                <n-button strong secondary round text-color="#FFFFFF" size="large">
                    Get all Access 
                </n-button>
            </div>
        </div>
    </nav>
    <hr>
</template>
<script>
import { NButton } from 'naive-ui';
import { defineComponent } from 'vue';

export default defineComponent ({ 
    components: {
        NButton
    }
})
</script>

<style scoped>

* {
    font-size: 1.5rem;
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
}

hr {
    opacity: 20%;
}

img {
    width: 90px;
    /* border: 1px solid blue; */
}

nav {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 1rem 1rem;
    margin: 0 1rem;
}

.left-content {
    display: flex;
    align-items: center;
}

.right-content {
    display: flex;
    align-items: center;
    margin-right: 1rem;
}

.right-content .content ul {
    display: flex;
    align-items: center;
}

.right-content .content ul li {
    list-style: none;
    font-size: 1rem;
    font-weight: lighter;
    margin-left: 1rem;
}

.right-content .content ul li:hover {
    color: gray;
}

.split-content {
    margin-left: 1rem;
    opacity: 20%;
}


.content-button > * {
    margin-left: 2rem;
    font-size: 1.1rem;
    font-weight: lighter;
}

.content-button .signin {
    border: none;
    background: none;
}

.content-button .signin:hover {
    color: gray;
}




</style>