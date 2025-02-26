<script setup>

</script>

<template>
    <div class="mx-auto w-5/6 flex gap-4">
        <div class="border-2 border-amber-900 rounded-2xl w-2/3 p-6">
            <p class="text-4xl text-center font-bold text-amber-900 mb-6">
                No et vols quedar sense el teu pa preferit?
            </p>
            <div class="space-y-6">
                <div class="flex items-center">
                    <span
                        class="mr-4 flex h-10 w-10 items-center justify-center rounded-full bg-amber-900 text-white font-bold">
                        1
                    </span>
                    <p class="text-amber-900 text-lg font-semibold">Selecciona el producte</p>
                </div>
                <div class="flex items-center">
                    <span
                        class="mr-4 flex h-10 w-10 items-center justify-center rounded-full bg-amber-900 text-white font-bold">
                        2
                    </span>
                    <p class="text-amber-900 text-lg font-semibold">Tria el dia</p>
                </div>
                <div class="flex items-center">
                    <span
                        class="mr-4 flex h-10 w-10 items-center justify-center rounded-full bg-amber-900 text-white font-bold">
                        3
                    </span>
                    <p class="text-amber-900 text-lg font-semibold">Recull el teu encàrrec</p>
                </div>
            </div>
        </div>

        <div class="bg-amber-900 rounded-2xl w-1/3 p-4 flex flex-col items-center justify-center">
            <img class="imagecistella w-auto max-h-48" src="/img/bread.svg" alt="Bread" />
            <p class="text-2xl text-center font-bold text-white mt-4">Veure tots els productes</p>
        </div>
    </div>
</template>

<style scoped>
.imagecistella {
    width: auto;
    max-width: 100%;
    height: auto;
    object-fit: contain;
}
</style>
