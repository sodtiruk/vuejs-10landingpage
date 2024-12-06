<template>
    <div class="section">
        <div class="container">

            <div class="total-card">
                <div class="card">
                    <img width="50px" src='data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjQiIGhlaWdodD0iMjQiIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0iIzAwMDAwMCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPHBhdGggZD0iTTEyIDYuNUMxMy4yNDI2IDYuNSAxNC4yNSA1LjQ5MjY0IDE0LjI1IDQuMjVDMTQuMjUgMy4wMDczNiAxMy4yNDI2IDIgMTIgMkMxMC43NTc0IDIgOS43NSAzLjAwNzM2IDkuNzUgNC4yNUM5Ljc1IDUuNDkyNjQgMTAuNzU3NCA2LjUgMTIgNi41Wk02LjE0OTc4IDQuMTc4MDNDNS4wMDY2NCAzLjY5Mjc5IDMuNjgxOTIgNC4yMjIzOSAzLjE4ODM0IDUuMzYxOTVDMi42OTMwNiA2LjUwNTQ1IDMuMjIyMyA3LjgyOTI3IDQuMzY5MzggOC4zMTYxN0w3LjM5MzA4IDkuNTk5NjZDNy43NjI0NyA5Ljc1NjQ1IDguMDAyMzUgMTAuMTE4OSA4LjAwMjM1IDEwLjUyMDJWMTMuNTU5N0w2LjEyMzM3IDE5LjAxNjdDNS43MTg4IDIwLjE5MTYgNi4zNDMzMiAyMS40NzIxIDcuNTE4MjYgMjEuODc2NkM4LjY5MzE5IDIyLjI4MTIgOS45NzM2NCAyMS42NTY3IDEwLjM3ODIgMjAuNDgxN0wxMS43NjM2IDE2LjQ1ODJDMTEuODQxIDE2LjIzMzQgMTIuMTU5IDE2LjIzMzQgMTIuMjM2NCAxNi40NTgyTDEzLjYyMTkgMjAuNDgxOUMxNC4wMjY0IDIxLjY1NjkgMTUuMzA2OSAyMi4yODE0IDE2LjQ4MTggMjEuODc2OEMxNy42NTY4IDIxLjQ3MjMgMTguMjgxMyAyMC4xOTE4IDE3Ljg3NjcgMTkuMDE2OUwxNi4wMDIzIDEzLjU2VjEwLjUxODFDMTYuMDAyMyAxMC4xMTY4IDE2LjI0MjIgOS43NTQzOCAxNi42MTE2IDkuNTk3NTlMMTkuNjMwNCA4LjMxNjE3QzIwLjc3NzUgNy44MjkyNyAyMS4zMDY4IDYuNTA1NDUgMjAuODExNSA1LjM2MTk1QzIwLjMxNzkgNC4yMjIzOSAxOC45OTMyIDMuNjkyNzkgMTcuODUgNC4xNzgwM0wxNi4yNDQgNC44NTk3M0MxNS45MDMzIDUuMDA0MzUgMTUuNjY1NyA1LjI4MjU2IDE1LjU0OTIgNS41OTA2N0MxNS4wMDcyIDcuMDI0OTkgMTMuNjIxNSA4LjA0Mjk1IDEyIDguMDQyOTVDMTAuMzc4NCA4LjA0Mjk1IDguOTkyNzIgNy4wMjUgOC40NTA2NyA1LjU5MDdDOC4zMzQyMyA1LjI4MjYgOC4wOTY1OCA1LjAwNDM5IDcuNzU1ODkgNC44NTk3OEw2LjE0OTc4IDQuMTc4MDNaIiBmaWxsPSIjMDAwMDAwIi8+Cjwvc3ZnPgo=' alt='ic_fluent_accessibility_24_filled' />
                    <div class="content">
                        <h1>Diverse components</h1>
                        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Doloremque, voluptas.</p>
                    </div>
                </div>
                <div class="card">
                    <img width="50px" src='data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjQiIGhlaWdodD0iMjQiIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0iIzAwMDAwMCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPHBhdGggZD0iTTEyIDYuNUMxMy4yNDI2IDYuNSAxNC4yNSA1LjQ5MjY0IDE0LjI1IDQuMjVDMTQuMjUgMy4wMDczNiAxMy4yNDI2IDIgMTIgMkMxMC43NTc0IDIgOS43NSAzLjAwNzM2IDkuNzUgNC4yNUM5Ljc1IDUuNDkyNjQgMTAuNzU3NCA2LjUgMTIgNi41Wk02LjE0OTc4IDQuMTc4MDNDNS4wMDY2NCAzLjY5Mjc5IDMuNjgxOTIgNC4yMjIzOSAzLjE4ODM0IDUuMzYxOTVDMi42OTMwNiA2LjUwNTQ1IDMuMjIyMyA3LjgyOTI3IDQuMzY5MzggOC4zMTYxN0w3LjM5MzA4IDkuNTk5NjZDNy43NjI0NyA5Ljc1NjQ1IDguMDAyMzUgMTAuMTE4OSA4LjAwMjM1IDEwLjUyMDJWMTMuNTU5N0w2LjEyMzM3IDE5LjAxNjdDNS43MTg4IDIwLjE5MTYgNi4zNDMzMiAyMS40NzIxIDcuNTE4MjYgMjEuODc2NkM4LjY5MzE5IDIyLjI4MTIgOS45NzM2NCAyMS42NTY3IDEwLjM3ODIgMjAuNDgxN0wxMS43NjM2IDE2LjQ1ODJDMTEuODQxIDE2LjIzMzQgMTIuMTU5IDE2LjIzMzQgMTIuMjM2NCAxNi40NTgyTDEzLjYyMTkgMjAuNDgxOUMxNC4wMjY0IDIxLjY1NjkgMTUuMzA2OSAyMi4yODE0IDE2LjQ4MTggMjEuODc2OEMxNy42NTY4IDIxLjQ3MjMgMTguMjgxMyAyMC4xOTE4IDE3Ljg3NjcgMTkuMDE2OUwxNi4wMDIzIDEzLjU2VjEwLjUxODFDMTYuMDAyMyAxMC4xMTY4IDE2LjI0MjIgOS43NTQzOCAxNi42MTE2IDkuNTk3NTlMMTkuNjMwNCA4LjMxNjE3QzIwLjc3NzUgNy44MjkyNyAyMS4zMDY4IDYuNTA1NDUgMjAuODExNSA1LjM2MTk1QzIwLjMxNzkgNC4yMjIzOSAxOC45OTMyIDMuNjkyNzkgMTcuODUgNC4xNzgwM0wxNi4yNDQgNC44NTk3M0MxNS45MDMzIDUuMDA0MzUgMTUuNjY1NyA1LjI4MjU2IDE1LjU0OTIgNS41OTA2N0MxNS4wMDcyIDcuMDI0OTkgMTMuNjIxNSA4LjA0Mjk1IDEyIDguMDQyOTVDMTAuMzc4NCA4LjA0Mjk1IDguOTkyNzIgNy4wMjUgOC40NTA2NyA1LjU5MDdDOC4zMzQyMyA1LjI4MjYgOC4wOTY1OCA1LjAwNDM5IDcuNzU1ODkgNC44NTk3OEw2LjE0OTc4IDQuMTc4MDNaIiBmaWxsPSIjMDAwMDAwIi8+Cjwvc3ZnPgo=' alt='ic_fluent_accessibility_24_filled' />
                    <div class="content">
                        <h1>Diverse components</h1>
                        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Doloremque, voluptas.</p>
                    </div>
                </div>
                <div class="card">
                    <img width="50px" src='data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjQiIGhlaWdodD0iMjQiIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0iIzAwMDAwMCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPHBhdGggZD0iTTEyIDYuNUMxMy4yNDI2IDYuNSAxNC4yNSA1LjQ5MjY0IDE0LjI1IDQuMjVDMTQuMjUgMy4wMDczNiAxMy4yNDI2IDIgMTIgMkMxMC43NTc0IDIgOS43NSAzLjAwNzM2IDkuNzUgNC4yNUM5Ljc1IDUuNDkyNjQgMTAuNzU3NCA2LjUgMTIgNi41Wk02LjE0OTc4IDQuMTc4MDNDNS4wMDY2NCAzLjY5Mjc5IDMuNjgxOTIgNC4yMjIzOSAzLjE4ODM0IDUuMzYxOTVDMi42OTMwNiA2LjUwNTQ1IDMuMjIyMyA3LjgyOTI3IDQuMzY5MzggOC4zMTYxN0w3LjM5MzA4IDkuNTk5NjZDNy43NjI0NyA5Ljc1NjQ1IDguMDAyMzUgMTAuMTE4OSA4LjAwMjM1IDEwLjUyMDJWMTMuNTU5N0w2LjEyMzM3IDE5LjAxNjdDNS43MTg4IDIwLjE5MTYgNi4zNDMzMiAyMS40NzIxIDcuNTE4MjYgMjEuODc2NkM4LjY5MzE5IDIyLjI4MTIgOS45NzM2NCAyMS42NTY3IDEwLjM3ODIgMjAuNDgxN0wxMS43NjM2IDE2LjQ1ODJDMTEuODQxIDE2LjIzMzQgMTIuMTU5IDE2LjIzMzQgMTIuMjM2NCAxNi40NTgyTDEzLjYyMTkgMjAuNDgxOUMxNC4wMjY0IDIxLjY1NjkgMTUuMzA2OSAyMi4yODE0IDE2LjQ4MTggMjEuODc2OEMxNy42NTY4IDIxLjQ3MjMgMTguMjgxMyAyMC4xOTE4IDE3Ljg3NjcgMTkuMDE2OUwxNi4wMDIzIDEzLjU2VjEwLjUxODFDMTYuMDAyMyAxMC4xMTY4IDE2LjI0MjIgOS43NTQzOCAxNi42MTE2IDkuNTk3NTlMMTkuNjMwNCA4LjMxNjE3QzIwLjc3NzUgNy44MjkyNyAyMS4zMDY4IDYuNTA1NDUgMjAuODExNSA1LjM2MTk1QzIwLjMxNzkgNC4yMjIzOSAxOC45OTMyIDMuNjkyNzkgMTcuODUgNC4xNzgwM0wxNi4yNDQgNC44NTk3M0MxNS45MDMzIDUuMDA0MzUgMTUuNjY1NyA1LjI4MjU2IDE1LjU0OTIgNS41OTA2N0MxNS4wMDcyIDcuMDI0OTkgMTMuNjIxNSA4LjA0Mjk1IDEyIDguMDQyOTVDMTAuMzc4NCA4LjA0Mjk1IDguOTkyNzIgNy4wMjUgOC40NTA2NyA1LjU5MDdDOC4zMzQyMyA1LjI4MjYgOC4wOTY1OCA1LjAwNDM5IDcuNzU1ODkgNC44NTk3OEw2LjE0OTc4IDQuMTc4MDNaIiBmaWxsPSIjMDAwMDAwIi8+Cjwvc3ZnPgo=' alt='ic_fluent_accessibility_24_filled' />
                    <div class="content">
                        <h1>Diverse components</h1>
                        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Doloremque, voluptas.</p>
                    </div>
                </div>
            </div>

            <div class="component">
                <p class="top">Component</p>
                <h1>Stunning UI componentns ready for launch</h1>
                <p class="detail">Lorem ipsum dolor sit amet consectetur adipisicing elit. Velit a optio quis eius exercitationem, ex cupiditate? Ipsam nisi cum possimus!</p>
                <button>Explore Components</button>
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
    margin-top: 3rem;
}

.container {
    max-width: 1040px;
    margin: 0 auto;
}

.total-card {
    display: flex;
}

.card {
    display: flex;
    width: 33%;
    padding: 1rem;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    font-weight: lighter;
}

.card *{
    margin-right: 3px; 
}

.card img {
    margin-bottom: 2.8rem;
}

.card .content p {
    color: gray; 
    font-size: 1rem;
}




.component {
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    font-weight: lighter;
    margin-top: 3rem;
    
}

.component {
    width: 50%;
}

.component .top {
    font-size: 18px;
    color: #22A45F;
}

.component h1 {
    font-size: 2.5rem;
}

.component .detail {
    font-size: 18px;
    color: gray;
}

.component button {
    border: 1px solid #22A45F;
    background: none;
    width: 18rem;
    padding: 1rem;
    margin-top: 1rem;
    font-size: 18px;
    font-weight: bold;
    color: #22A45F;
    border-radius: 22px;
}

.component button:hover {
    background-color: #22A45F; 
    color: white;
}








</style>

