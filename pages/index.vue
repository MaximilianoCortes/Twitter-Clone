<template>
    <div class="relative flex flex-col items-center justify-start 2xl:w-7/12 xl:w-7/12 lg:w-7/12 sm:w-7/12 min-h-screen 2xl:ml-[280px] xl:ml-[280px] lg:ml-[80px] sm:ml-[80px]">
        <TwitNav/>
        <WhatsHappening/>
        <TwitPost/>
    </div>
    <aside class="2xl:w-5/12 xl:w-5/12 lg:w-5/12 sm:w-5/12 min-h-screen border-l-[0.5px] border-useGray relative flex flex-col justify-start gap-2 items-center px-5">
        <TwitSearch />
        <TrendsForYou />
        <WhoToFollow />
    </aside>
</template>

<script setup>
useHead({
    title: 'home',
    meta: [
        { name: 'description', content: 'My amazing site.' }
    ],
})
</script>

