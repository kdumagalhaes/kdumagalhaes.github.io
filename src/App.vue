<template>
    <Profile
        picSrc="../assets/img/profile-pic.png"
        text="Graduated in Advertising, Software Development student currently
                working as Lead Product Specialist... and sometimes a musician
                :)"
    />
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { Profile } from '@/components/index'

export default defineComponent({
    components: {
        Profile,
    },
})
</script>

<style lang="scss"></style>
