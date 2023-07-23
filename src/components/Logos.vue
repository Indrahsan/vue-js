<template>
    <div class="logos-wrapper">
        <h2 class="title-header">
            Find Best Logos
        </h2>
        <div class="item-logos">
            <img class="logo" src="../assets/nike.svg" alt="nike">
        </div>
        <div class="item-logos">
            <img class="logo" src="../assets/adidas.svg" alt="adidas">
        </div>
         <div class="item-logos">
            <img class="logo" src="../assets/nike.svg" alt="nike">
        </div>
        <div class="item-logos">
            <img class="logo" src="../assets/adidas.svg" alt="adidas">
        </div>
         <div class="item-logos">
            <img class="logo" src="../assets/nike.svg" alt="nike">
        </div>
        <div class="item-logos">
            <img class="logo" src="../assets/adidas.svg" alt="adidas">
        </div>
         <div class="item-logos">
            <img class="logo" src="../assets/nike.svg" alt="nike">
        </div>
        <div class="item-logos">
            <img class="logo" src="../assets/adidas.svg" alt="adidas">
        </div>
         <div class="item-logos">
            <img class="logo" src="../assets/nike.svg" alt="nike">
        </div>
        <div class="item-logos">
            <img class="logo" src="../assets/adidas.svg" alt="adidas">
        </div>
         <div class="item-logos">
            <img class="logo" src="../assets/nike.svg" alt="nike">
        </div>
        <div class="item-logos">
            <img class="logo" src="../assets/adidas.svg" alt="adidas">
        </div>
    </div>
</template>

<script>
export default {
    name: 'LogosVue'
}
</script>

<style scoped>
.logos-wrapper{
    width: 70%;
    overflow: hidden;
    margin: auto;
}

.item-logos{
    float: left;
    margin-right: 70px;
    margin-bottom: 20px;
    width: 150px;
    height: 150px;
}

.item-logos .logo{
    width: 150px;
    height: 150px;
}

.title-header {
    margin-bottom: 80px;
    text-align: left;
}
</style>