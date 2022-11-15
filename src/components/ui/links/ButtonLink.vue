<template>
    <a href="/" class="group/link c-button-link">
        <span class="c-line c-top"></span>
        <span class="c-line c-right"></span>
        <span class="c-line c-bottom"></span>
        <span class="c-line c-left"></span>
        <slot></slot>
    </a>
</template>
<style>
.c-button-link {
    @apply text-white px-6 py-3 block relative;
}

.c-line {
    @apply block absolute transition-[top,right,bottom,left] duration-300 ease-in-out;
    @apply from-white/50 to-white ;
}

.c-line.c-top {
    @apply h-px bg-gradient-to-r;
    @apply top-0 left-0 right-full;
    @apply group-hover/link:right-0;
}

.c-line.c-right {
    @apply w-px bg-gradient-to-b;
    @apply top-0 bottom-full right-0;
    @apply group-hover/link:bottom-0;
}

.c-line.c-bottom {
    @apply h-px bg-gradient-to-l;
    @apply bottom-0 right-0 left-full;
    @apply group-hover/link:left-0;
}

.c-line.c-left {
    @apply w-px bg-gradient-to-t;
    @apply left-0 bottom-0 top-full;
    @apply group-hover/link:top-0;
}
</style>