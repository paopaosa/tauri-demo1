<template>
    <div>
        <h1>About us</h1>
        <input type="text" v-model="search">
        <p>search term - {{ search }}</p>
        <div v-for="name in names" :key="name">{{ name }}</div>
    </div>
</template>

<script lang="ts">
import { defineComponent, ref } from 'vue'

export default defineComponent({
    setup() {
        const names = ref(['mario', 'yoshi', 'luigi', 'toad', 'browser', 'koopa', 'peach'])
        const search = ref('')
        return { names, search }
    }
})
</script>

<style scoped>
</style>