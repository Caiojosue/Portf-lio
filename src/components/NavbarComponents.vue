<template>
    <nav class="bg-rose-700 text-white py-4 px-8 flex justify-between items-center">
        <h1 class="text-lg font-bold">Portifolio</h1>
        <ul class="flex gap-6">
            <li>
                <router-link to="/" class="hover:underline">Inicio</router-link>
            </li>
            <li>
                <router-link to="/about" class="hover:underline">Sobre</router-link>
            </li>
            <li>
                <router-link to="/contact" class="hover:underline">Contato</router-link>
            </li>
        </ul>
    </nav>
</template>