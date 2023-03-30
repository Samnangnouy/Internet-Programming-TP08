<script setup>
</script>

<template>
    <div id="app">
        <div class="wrapper">
            <div class="left-side">
                <div class="left">
                    <div>
                        <img src="./assets/logo.svg" style="height: 100px;">
                    </div>
                    <div class="content">
                        <P class="welcome">Welcome</P>
                        <p>Authentication app~~</p>
                        <p>
                            <router-link to="/"><button id="login" @click="clickLogin=true">Login</button></router-link>
                            <router-link to="/register" @click="clickLogin=false"><button id="register">Register</button></router-link>
                        </p>
                    </div>
                </div>
            </div>
            <router-view></router-view>
        </div>
    </div>
</template>
<style scoped>
* {
    font-family: sans-serif;
}
.wrapper {
    width: 70%;
    height: 90vh;
    margin: auto;
    border: 5px solid black;
    display: flex;
}
.left-side {
    width: 50%;
    height: 100%;
    display: flex;
    align-items: center;
}
.left-side .left{
    height: 140px;
    margin-left: 5%;
    display: flex;
    align-items: center;
    column-gap: 20px;
}
.left-side .welcome{
    font-size: 1.7rem;
    font-weight: 500;
    color: rgb(16, 203, 88);
    margin-bottom: 0;
}
.left-side .content{
    display: flex;
    flex-direction: column;
}
</style>
