<template>
    <header class="w-full grid-container py-4">
        <div class="flex items-center gap-6 justify-between">
            <NuxtLink to="/" class="w-40">
                <img src="" alt="">
            </NuxtLink>
            <nav class="flex items-center gap-6">
                <NuxtLink class="flex flex-col after:w-0 after:h-px after:bg-[#292929] after:duration-500 after:transition-all hover:after:w-full">Главная</NuxtLink>
                <NuxtLink class="flex flex-col after:w-0 after:h-px after:bg-[#292929] after:duration-500 after:transition-all hover:after:w-full">Каталог</NuxtLink>
                <NuxtLink class="flex flex-col after:w-0 after:h-px after:bg-[#292929] after:duration-500 after:transition-all hover:after:w-full">О нас</NuxtLink>
                <div class="flex items-center gap-4">
                    <NuxtLink>
                        <Icon class="text-3xl transition-all duration-500 hover:opacity-50" name="material-symbols:shopping-cart"/>
                    </NuxtLink>
                    <NuxtLink>
                        <Icon class="text-3xl transition-all duration-500 hover:opacity-50" name="material-symbols:person"/>
                    </NuxtLink>
                </div>
            </nav>
        </div>
    </header>
</template>

<script setup>

</script>