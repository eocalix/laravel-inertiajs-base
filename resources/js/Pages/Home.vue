<script setup>
import MainLayout from '../Layouts/MainLayout.vue';
import { Head } from '@inertiajs/vue3';

</script>
<script>
export default {
    layout: MainLayout,
}
</script>
<template>
    <Head title="Home"></Head>
    <h1 class="bg-success">Hola Mundo</h1>
    <i class="fa-solid fa-ring"></i>
</template>