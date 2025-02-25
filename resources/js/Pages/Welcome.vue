<script setup>
import { Head, Link } from '@inertiajs/vue3';
import Menu from '@/Components/Menu/Menu.vue';
import WelcomeText from '@/Components/WelcomePage/WelcomeText.vue';
</script>

<template>

    <Head title="Llonguet de Perelada" />
    <div class=" min-h-screen">
        <Menu />
        <div class="pt-24">
            <WelcomeText />
        </div>
    </div>

</template>
