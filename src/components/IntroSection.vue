<script>
    export default {
        name: 'IntroSection'
    }
</script>

<template>
    <section id="container">
        <img src="../images/Vue_logo.png" alt="Vue logo">
        <h1>Welcome to Vue.js</h1>
        <p id="subtitle">Become a coding ninja with the fastest-growing JavaScript framework</p>
        <p id="awesome">Awesome!</p>
    </section>

</template>

<style scoped>
    @import url('https://fonts.googleapis.com/css2?family=Inter:wght@800&display=swap');
    
    #container {
        display: flex;
        flex-direction: column;
        align-items: center;
        text-align: center;
        font-family: Inter;
        color: #2B2F30;
        height: 300px;
        
    }
    h1 {
        font-size: 50px;
        margin-top:20px;
    }
    #subtitle {
        font-size: 14px;
        width: 309px;
        height: 40px;
        line-height: 20px;
        margin-top:20px;
    }
    #awesome {
        color: #FFFFFF;
        background-color: #34495E;
        border-radius: 15px;
        font-size: 14px;
        padding: 5px 25px;
        margin-top:30px;
    }
</style>