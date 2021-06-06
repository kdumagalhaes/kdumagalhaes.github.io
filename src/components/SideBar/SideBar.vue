<template>
    <aside class="sidebar">
        <Profile
            picSrc="../assets/img/profile-pic.png"
            text="Graduated in Advertising, Software Development student currently
                working as Lead Product Specialist... and sometimes a musician
                :)"
        />
        <Status company="VTEX" studying="VueJS" country="Brazil" />
        <Navigation />
        <SocialMedia />
    </aside>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { Navigation, Profile, SocialMedia, Status } from './index'

export default defineComponent({
    components: {
        Profile,
        Status,
        SocialMedia,
        Navigation,
    },
})
</script>

<style scoped lang="scss">
.sidebar {
    background-color: olivedrab;
    height: 100vh;
    width: 100%;
    max-width: 450px;
    padding: 70px 40px;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    background-color: $color3;
}
</style>
