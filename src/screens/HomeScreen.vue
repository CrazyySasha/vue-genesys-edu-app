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
        <header class="bg-[url(/assets/images/ellipse.svg)] bg-no-repeat min-h-screen">

        </header>

        <section class="h-[400vh]">

        </section>
    </main>

</template>