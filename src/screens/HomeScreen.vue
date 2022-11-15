<script setup>
import CButtonLink from '../components/ui/links/ButtonLink.vue';
import CLogo from '../components/Logo.vue';

</script>
<template>
    <header class="flex justify-between items-center px-8 font-comfortaa bg-dark fixed top-0 inset-x-0">
        <a href="" class="text-white text-xl px-6 py-3 -mx-6 block">
            <CLogo></CLogo>
        </a>
        <nav class="py-7">
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
    <main>
        <header class="bg-[url(/assets/images/ellipse.svg)] bg-no-repeat min-h-screen">

        </header>
    </main>

</template>