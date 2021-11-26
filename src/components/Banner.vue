<template>
    <div id="main-banner">
        <h1>Make Your Burger</h1>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
    #main-banner {
        background: url('/img/burger.jpg') center no-repeat;
        background-size: cover;
        height: 600px;
        display: flex;
        align-items: center;
        justify-content: flex-start;
    }

    #main-banner h1 {
        color: #fff;
        text-align: center;
        font-size: 60px;
        background-color: #222;
        padding: 20px 40px;
    }
</style>