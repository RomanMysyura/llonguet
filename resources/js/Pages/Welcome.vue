<script setup>
import { Head, Link } from '@inertiajs/vue3';
import Menu from '@/Components/Menu/Menu.vue';
import WelcomeText from '@/Components/WelcomePage/WelcomeText.vue';
import WebShopInvitation from '@/Components/WelcomePage/WebShopInvitation.vue';
import ProductCarrousel from '@/Components/WelcomePage/ProductCarrousel.vue';
</script>

<template>

    <Head title="Llonguet de Perelada" />
    <div class=" min-h-screen">
        <Menu />
        <div class="pt-32">
            <WelcomeText />
        </div>
        <div class="mt-5">
            <WebShopInvitation />
        </div>
        <div class="mt-5">
            <ProductCarrousel />
        </div>
    </div>

</template>
