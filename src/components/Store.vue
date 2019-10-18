<template>
    <div>
        <FiltreStore/>
        <ProductsBM/>
    </div>
</template>

<script>
    import FiltreStore from "@/components/FiltreStore";
    import ProductsBM from "@/components/ProductsBM";
    export default {
        name: "Store",
        components:{
            FiltreStore,
            ProductsBM
        }
    }
</script>

<style scoped>

</style>
