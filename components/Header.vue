<template>
    <header class="grid-container py-6 md:py-8 xl:py-12 relative">
        <div class="flex items-center justify-between py-3 px-8 rounded-full bg-[#1C1C1C] text-white z-[5] border border-[#262626] text-xs md:text-sm xl:text-lg">
            <NuxtLink to="/" @click="isMenuShow = false" class="flex items-center gap-1">
                <img src="/images/header/logo.png" alt="">
                <span class="font-semibold text-xl">FireBanK</span>
            </NuxtLink>
            <nav class="flex items-center gap-6 max-lg:absolute max-lg:flex-col max-lg:w-[calc(100%-40px)] max-sm:w-[calc(100%-30px)] max-lg:left-1/2 max-lg:-translate-x-1/2 max-lg:z-[5] max-lg:py-4 max-lg:rounded-2xl max-lg:bg-[#1C1C1C] max-lg:border max-lg:border-[#262626] max-lg:transition-all max-lg:duration-500" :class="isMenuShow ? 'max-lg:top-full' : 'max-lg:top-0 max-lg:-translate-y-full'">
                <NuxtLink class="headerLink" to="/" @click="isMenuShow = false">Home</NuxtLink>
                <NuxtLink class="headerLink" to="/career" @click="isMenuShow = false">Careers</NuxtLink>
                <NuxtLink class="headerLink" to="/about" @click="isMenuShow = false">About</NuxtLink>
                <NuxtLink class="headerLink" to="/security" @click="isMenuShow = false">Security</NuxtLink>
                <div class="flex items-center gap-5 lg:hidden">
                    <NuxtLink to="/" @click="isMenuShow = false">Sign Up</NuxtLink>
                    <NuxtLink to="/" @click="isMenuShow = false" class="py-3 px-7 rounded-full bg-[#CAFF33] text-black">Login</NuxtLink>
                </div>
            </nav>
            <div class="flex items-center gap-5 max-lg:hidden">
                <NuxtLink to="/" @click="isMenuShow = false">Sign Up</NuxtLink>
                <NuxtLink to="/" @click="isMenuShow = false" class="py-3 px-7 rounded-full bg-[#CAFF33] text-black">Login</NuxtLink>
            </div>
            <button class="py-3 px-4 rounded-full bg-[#CAFF33] lg:hidden" @click="isMenuShow = !isMenuShow">
                <img src="/images/header/menu.png" alt="">
            </button>
        </div>
        <img src="/images/header/topBlock.png" alt="" class="col-span-full absolute top-0 left-0">
    </header>
</template>

<script setup>
    const isMenuShow = ref(false)
</script>

<style>
    .headerLink {
        padding: 8px 20px;
        border-radius: 100px;
    }
    .router-link-active.headerLink {
        border-width: 1px;
        border-color: #26262683;
        background-image: url(/images/header/link.png);
    }
</style>