<template>
    <div class="px-6 bg-gray-700 navbar opacity-50 rounded-r">
        <div class="flex justify-between py-2">
            <div>
                <i  @click="$store.state.removeX = false" class="fa-solid fa-bars text-white text-xl  duration-200  p-1 rounded-full px-2 hover:bg-gray-500"></i>
            </div>
            <div class="space-x-4" @click="$store.state.removeX = false">
                <i class="fa-solid fa-magnifying-glass text-white text-xl  duration-200  p-1 rounded-full px-2 hover:bg-gray-500"></i>
                <i class="fa-solid fa-heart text-white text-xl  duration-200  p-1 rounded-full px-2 hover:bg-gray-500"></i>
                <i class="fa-solid fa-circle-half-stroke text-white text-xl  duration-200  p-1 rounded-full px-2 hover:bg-gray-500"></i>
                <i class="fa-solid fa-ellipsis-vertical text-white text-xl  duration-200  p-1 rounded-full px-2 hover:bg-gray-500"></i>
            </div>
        </div>
        <div class="mt-14">
            <h1 class="pb-6 text-2xl font-serif text-white">Vuetify Vazifa</h1>
        </div>
    </div>
</template>


<script>
export default {
    name: 'NavBar',
}
</script>

<style scoped>
    .navbar {
        background: url('../../public/naturee.jpg');
    }
</style>