<script setup>
import { PlusIcon } from '@heroicons/vue/20/solid'
</script>

<script type="text/javascript">
export default {

};
</script>

<template>

    <div class="md:h-screen w-screen px-4 pt-6 lg:pt-10 max-w-7xl mx-auto flex flex-col justify-center items-center pb-20 lg:pb-40">

        <!-- Logo -->
        <div class="flex items-center justify-center mb-14 mt-10 md:mt-4">
            <img src="../../assets/img/pepper-logo-dark.svg" class="h-6" />
        </div>

        <div class="w-full mb-14">
            <h3 class="font-semibold text-lg mb-14 text-center">Escolha a área de membros que deseja acessar:</h3>

            <div class="w-full grid grid-cols-1 sm:grid-cols-3 md:grid-cols-4 xl:grid-cols-5 gap-4">

                <router-link to="/area" class="w-full overflow-hidden">
                    <div class="thumb-container w-full rounded-lg overflow-hidden">
                        <img class="w-full aspect-video bg-slate-500 bg-opacity-10" src="https://nerdreactor.com/wp-content/uploads/2017/09/The-Walking-Dead-_S8_14x48BB_REF1-thumb.jpg" />
                    </div>
                    <div class="px-1 py-3">
                        <div class="font-semibold text-sm mb-2">Área de membros exemplo</div>
                    </div>
                </router-link>

                <router-link to="/area" class="w-full overflow-hidden">
                    <div class="thumb-container w-full rounded-lg overflow-hidden">
                        <img class="w-full aspect-video bg-slate-500 bg-opacity-10" src="https://wallpaperset.com/w/full/3/f/d/22523.jpg" />
                    </div>
                    <div class="px-1 py-3">
                        <div class="font-semibold text-sm mb-2">Área de membros Medicina</div>
                    </div>
                </router-link>

            </div>
        </div>


        <div class="flex items-center justify-center mb-14">
            <button type="button" class="w-full inline-flex justify-center items-center rounded-md border border-pepper-primary bg-pepper-primary px-4 py-3 text-sm font-semibold text-white shadow-sm hover:bg-danger-700 focus:outline-none focus:ring-1 focus:ring-danger-500 focus:ring-offset-1">
                <PlusIcon class="-ml-1 mr-1 h-4 w-4 font-bold" aria-hidden="true" />
                <span>Criar nova área de membros</span>
            </button>
        </div>


    </div>
</template>

<style scoped>

</style>