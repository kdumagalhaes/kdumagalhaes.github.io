<template>
    <Profile
        picSrc="../assets/img/profile-pic.png"
        text="Graduated in Advertising, Software Development student currently
                working as Lead Product Specialist... and sometimes a musician
                :)"
    />
    <Status company="VTEX" studying="VueJS" country="Brazil" />
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { Profile, Status } from '@/components/index'

export default defineComponent({
    components: {
        Profile,
        Status,
    },
})
</script>

<style lang="scss"></style>
