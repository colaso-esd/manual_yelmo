<script setup>
import Logo from './Logo.vue';
</script>

<template>
    <aside class="sidebar">
        <div class="side_wrapper">
            <div class="logo">
                <div class="svg">
                    
                    <div class="first_level">

                        <NuxtLink to="/entry">
                            <Logo />
                        </NuxtLink>

                    </div>
                </div>
            </div>
            <div class="navigation">
                <div class="first_level">

                    <NuxtLink to="/logotipo">Logotipo</NuxtLink>

                </div>
                <div class="first_level">

                    <NuxtLink to="/color">Color</NuxtLink>

                </div>

                <div class="first_level">

                    <NuxtLink to="/tipografia">Tipografía</NuxtLink>

                </div>
                <div class="first_level">

                    <NuxtLink to="/tratamiento">Tratamiento de imagen</NuxtLink>

                </div>
                <div class="first_level">

                    <NuxtLink to="/reticula">Retícula</NuxtLink>

                </div>
                <div class="first_level">

                    <NuxtLink to="/estructura">Estructura compositiva</NuxtLink>

                </div>
                <div class="first_level">

                    <NuxtLink to="/aplicaciones">Aplicaciones</NuxtLink>

                </div>
                <div class="first_level">

                    <NuxtLink to="/usosmalos">Usos incorrectos</NuxtLink>

                </div>

            </div>
        </div>
    </aside>
</template>

<style lang="sass" scoped>
.sidebar
    @apply bg-slate-100 col-start-1 col-end-2 sticky top-0 h-full
    .side_wrapper
        @apply overflow-auto
        .logo
            @apply bg-[#FD4E62] flex px-8 items-center h-[60px] 
        .navigation
            @apply p-12 flex flex-col gap-4 m-2 divide-y divide-slate-500
            .first_level
                @apply text-lg text-slate-800 font-semibold py-6 


</style>