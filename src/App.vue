// Asosiy html codlar yoziladigan maydon
<template>
    <AsideLeft/>
    <div class="wrapper">
        <header-item/>
    </div>
</template>


// --------------------------------------------


// Asosiy logika Java Script yoziladigan maydon 
<script>
    // HEADER ITEM FAYLNI IMPORT QILISH
    import HeaderItem from './components/HeaderItem.vue';
    import AsideLeft from './components/AsideLeft.vue';

    // IMPORT QILINGAN FAYLNI TANISHTIRISH (REGISTRATSIYA)
    export default {
        name: 'App',
        components: {
            HeaderItem,
            AsideLeft
        }
    }

</script>


// --------------------------------------------


// Asosiy style yoziladigan maydon
<style>
    @import url('https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;700&display=swap');
    *{
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }
    button {
        border: 0;
        background: 0;
    }
    input{
        border: 0;
    }
    input:hovet {
        border: 0;
    }
</style>
