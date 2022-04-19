 
<template>
    <div class="root">{{ userStore.name }}</div>
</template>

<script lang="ts" setup>
import { useUserStore } from '@/store/user'

const userStore = useUserStore()
</script>
<style lang="scss">
.root {
    color: red;
}
</style>
