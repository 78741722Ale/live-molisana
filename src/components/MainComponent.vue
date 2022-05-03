<template>
    <main>
        <h1>Lista Prodotti</h1>
        <!-- Componente ProductList -->
        <ProductList />
    </main>
</template>

<script>
import ProductList from '@/components/ProductList.vue';

export default {
    name: "MainComponent",
    // nei componenti Data è una function
    components : {
        ProductList
    },
};
</script>
