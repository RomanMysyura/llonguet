<script setup>

</script>

<template>
    <header
        class="fixed inset-x-0 top-0 z-30 mx-auto w-full max-w-screen-md border border-gray-00 bg-white/80 py-3 shadow backdrop-blur-lg md:top-4 md:rounded-3xl lg:max-w-screen-xl">
        <div class="px-4">
            <div class="flex items-center justify-between">
                <div class="flex shrink-0">
                    <a class="flex items-center" href="/">
                        <img class="h-12 w-auto" src="/img/logollonguet.avif" alt="Logo">
                    </a>
                </div>
                <div class="hidden md:flex md:items-center md:justify-center md:gap-5">
                    <a class="inline-block rounded-lg px-2 py-1 text-lg font-bold text-black transition-all duration-200 hover:bg-gray-100 hover:text-amber-900"
                        href="#">Qui som</a>
                    <a class="inline-block rounded-lg px-2 py-1 text-lg font-bold text-black transition-all duration-200 hover:bg-gray-100 hover:text-amber-900"
                        href="#">Productes</a>
                    <a class="inline-block rounded-lg px-2 py-1 text-lg font-bold text-black transition-all duration-200 hover:bg-gray-100 hover:text-amber-900"
                        href="#">Contacte</a>
                    <a class="inline-block rounded-lg px-2 py-1 text-lg font-bold text-black transition-all duration-200 hover:bg-gray-100 hover:text-amber-900"
                        href="#">La nostra història</a>
                </div>
                <div class="flex items-center justify-end gap-3">
                    <a class="inline-flex items-center justify-center rounded-xl bg-amber-800 px-3 py-2 text-md font-semibold text-white shadow-sm transition-all duration-150 hover:bg-amber-700 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-blue-600"
                        href="/login">Iniciar sessió</a>
                </div>
            </div>
        </div>
    </header>
</template>
