<script setup>
import CButtonLink from '../components/ui/links/ButtonLink.vue';
import CLogo from '../components/Logo.vue';

</script>
<template>
    <header
        class="text-white flex justify-between items-center px-8 font-comfortaa backdrop-blur-sm shadow-sm fixed top-0 inset-x-0 mix-blend-lighten">
        <a href="" class=" text-xl px-6 py-3 -mx-6 block">
            <CLogo></CLogo>
        </a>
        <nav class="py-4">
            <ul class="flex text-xl -mx-6">
                <li>
                    <CButtonLink>Курсы</CButtonLink>
                </li>
                <li>
                    <CButtonLink>О нас</CButtonLink>
                </li>
                <li>
                    <CButtonLink>Менторы</CButtonLink>
                </li>
                <li>
                    <CButtonLink>Блог</CButtonLink>
                </li>
                <li>
                    <CButtonLink>Войти</CButtonLink>
                </li>
            </ul>
        </nav>
    </header>
    <main class="">
        <header class="bg-[url(/assets/images/ellipse.svg)] pt-28 bg-no-repeat min-h-screen flex justify-between px-8">
            <div class="w-5/12">
                <h1 class="text-white text-5xl font-comfortaa">
                    Lorem ipsum dolor sit amet.
                </h1>
                <p class="text-white text-base font-comfortaa py-16">
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut et massa mi. Aliquam in hendrerit urna.
                    Pellentesque sit amet sapien fringilla, mattis ligula consectetur, ultrices mauris. Maecenas vitae
                    mattis tellus.
                </p>
            </div>
            <div class="w-5/12">
                <div class="h-16 bg-gray-50">

                </div>
            </div>
        </header>

        <section class="h-[400vh]">

        </section>
    </main>

</template>