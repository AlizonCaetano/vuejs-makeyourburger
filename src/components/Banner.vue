<template>
    <div id="main-banner">
        <h1>Make Your Burger</h1>
    </div>
</template>

<script>
export default {
    name: "Banner"
}
</script>

<style scoped>

#main-banner {
    background-image: url('/img/burger.png');
    background-position: 0 -250px;
    background-size: cover;
    height: 500px;
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: flex-start;
}

#main-banner h1 {
    color: #fff;
    font-size: 60px;
    text-align: center;
    background-color: #222;
    padding: 20px 40px;
}
</style>