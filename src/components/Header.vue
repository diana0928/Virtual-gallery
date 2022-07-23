<template>
    <div class="flex justify-between bg-white p-8 shadow-lg text-black text-lg">
        <div><img class="h-16" src="../assets/lo.png"></div>
        <div class="flex">
        <router-link class="text-black uppercase px-2" :to="link.href" v-for="link in links" :key="link.name" v-text="link.name"></router-link>
        </div>
        <div>
            <router-link to="/contacto" class="btn font-bold uppercase bg-blue-500 px-10 py-3 rounded-full text-white hover:bg-white hover:text-blue-500 hover:border-2 hover:border-blue-500">Contact</router-link>
        </div>
    </div>
</template>
<script>
export default {
    data() {
        return {
            links : [
                {
                    name : 'Inicio',
                    href : '/',
                    icon : 'home'
                },
                {
                    name : 'Nosotros',
                    href : '/nosotros',
                    icon : 'about'
                }
            ]
        }
    },
}
</script>
