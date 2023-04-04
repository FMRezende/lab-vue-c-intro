<script>
    export default {
        name: 'USP'
    }
</script>

<template>
    <section id="USP-section">
        <article>
            <img class="USP-image" src="../images/USP-1.png" alt="Desktop Screen">
            <p class="USP-title">Performant</p>
            <p class="USP-text">Truly reactive, compiler-optimized rendering system that rarely requires manual optimization.</p>
        </article>
        <article>
            <img class="USP-image" src="../images/USP-2.png" alt="User with a laptop">
            <p class="USP-title">Approachable</p>
            <p class="USP-text">Builds on top of standard HTML, CSS and JavaScript with intuitive API and world-class documentation.</p>
        </article>
        <article>
            <img class="USP-image" src="../images/USP-3.png" alt="Desktop Screen">
            <p class="USP-title">Versatile</p>
            <p class="USP-text">A rich, incrementally adoptable ecosystem that scales between a library and a full-featured framework.</p>
        </article>
    </section>
</template>

<style scoped>
    @import url('https://fonts.googleapis.com/css2?family=Inria+Sans:wght@300;400;700&display=swap');
    #USP-section {
        background-color: #39B983;
        display: flex;
        align-items: center;
        justify-content: space-evenly;
        margin: 150px 0 40px;
        padding: 60px 0 30px;
        height: 312px;
        
     
    }
    #USP-section article {
        text-align: center;
        width: 170px;
    }
   .USP-title {
    font-size: 16px;
    font-family: 'Inter';
   }
   .USP-text {
    font-family: 'Inria Sans';
    min-height: 91px;
    min-width: 125px;
    font-size: 12px;
    padding: 10px;
   }
   @media (max-width: 599px) {
    #USP-section {
        flex-direction: column;
        margin-top: 150px;
        padding: 20px 0;
        background-color: #FFFFFF;
    }
    #USP-section article {
        padding: 20px;
        background-color: #39B983;
        margin: 20px;
        border-radius: 13px;
    }
   }
</style>