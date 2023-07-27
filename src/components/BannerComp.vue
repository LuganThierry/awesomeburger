<template>

    <div id="main-banner">
        <h1>Awesome Burger</h1>
    </div>

</template>


<script>

export default {
    name: 'BannerComp'
}

</script>

<style scoped>

    #main-banner {
        background-image: url('../../public/img/Hamburger1.jpg');
        background-size:contain;
        height: 240px;
        display: flex;
        align-items: center;
        justify-content: left;
    }

    #main-banner h1 {
        color: #003566;
        text-align: center;
        font-size: 60px;
        background-color: #FFD60A;
        padding: 15px 50px;
    }

</style>