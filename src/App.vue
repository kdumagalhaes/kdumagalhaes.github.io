<template>
    <div class="app">
        <SideBar />
        <AboutMe />
    </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { SideBar, AboutMe } from '@/components/index'

export default defineComponent({
    components: {
        SideBar,
        AboutMe,
    },
})
</script>

<style scoped lang="scss">
.app {
    display: flex;
}
</style>
