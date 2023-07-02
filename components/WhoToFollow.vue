<template>
<div class="w-full h-auto px-5 mt-2">
    <div class="bg-useGray h-auto rounded-xl overflow-hidden">
        <h3 class="text-normalWhite px-2 py-3 font-bold">Informadores recomendados</h3>
        <ul>
            <li v-for="follow in followProfile" :key="follow.id" class="flex p-3 gap-2 items-center justify-center cursor-pointer hover:bg-lowWhite transition duration-200">
                <div class="overflow-hidden">
                    <img :src="follow.p_image" class="w-10 h-10 object-cover rounded-full hover:brightness-90 transition duration-200" alt="profile image" />
                </div>
                <div class="flex flex-col flex-grow text-[13px]">
                    <span class="font-semibold text-normalWhite">{{ follow.p_name }}</span>
                    <span class="font-light text-lowsWhite">{{ follow.p_at }}</span>
                </div>
                <button class="bg-normalWhite px-3 py-1 rounded-l-2xl rounded-r-2xl text-[13px] font-semibold hover:brightness-90 transition duration-200">Follow</button>
            </li>
            <li class="text-sm text-useGreen p-2 py-4 hover:bg-lowWhite cursor-pointer">Mostrar mas</li>
        </ul>
    </div>
</div>
</template>

<script setup>
const followProfile = ref([
    {id:1, p_image:'/images/ub.jpg', p_name:'Ufrobook', p_at:'@Ufrobook'},
    {id:2, p_image:'/images/ea.jpeg', p_name:'Emergencias Araucania', p_at:'@EmergenciasAraucania'},
    {id:3, p_image:'/images/um.jpg', p_name:'Ufromedios', p_at:'@Ufromedios'},
])

</script>

