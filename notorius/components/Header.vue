<template>
    <div class="contenedor ">
        <img src="../assets/img/logo.png" alt="logo">
        <h1>GROWSHOP ONLINE</h1>
    </div>
</template>
<script>
export default {
    name:'Header'
}
</script>
<style lang="css" scoped>
    .contenedor{
        display: flex;
        margin-left: 15vw;

    }
    h1{
        text-align: center;
        font-size: 3vw;
    }
    img{
        width: 5vw;
        height: 5vw;
        margin-right: 32px;
    }
</style>