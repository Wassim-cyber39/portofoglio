<script setup>
import { useUserStore } from '@/stores/user'

const userStore = useUserStore()

function logout() {
    userStore.removeToken()
}
</script>

<template>
    <div>

        <slot />

        <footer class="p-6 flex flex-wrap items-center justify-between bg-black">

            <div class="flex mt-6 md:mt-0 items-center space-x-4">

            </div>
        </footer>
    </div>
</template>