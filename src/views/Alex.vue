<template>
    <div>
        <h1>Alex vagyok</h1>
        <p>A 2001. szeptember 11-ei terrortámadások (gyakori rövidítése: 9/11, ami a szeptember 11-ei dátum amerikai írásmódja; kimondva: szeptember tizenegy) az al-Káida terrorszervezet összehangolt öngyilkos merényletsorozata volt az Egyesült Államok ellen.</p>
        <img :src="kep" alt="poo">
    </div>
</template>

<script>
export default {
    data(){
        kep: './public/911.png'
    }
}
</script>

<style>

</style>