<template>
    <nav class="navigation">
        <ul class="navigation__list">
            <li><a href="#">about me</a></li>
            <li><a href="#">developer</a></li>
            <li><a href="#">musician</a></li>
            <li><a href="#">contact me</a></li>
        </ul>
    </nav>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({})
</script>

<style scoped lang="scss">
.navigation {
    .navigation__list {
        line-height: 33px;

        a {
            font-weight: $bold;
            text-decoration: none;
            color: $color2;
            font-size: 1.2rem;
        }
    }
}
</style>
