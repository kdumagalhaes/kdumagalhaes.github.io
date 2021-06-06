<template>
    <nav class="navigation">
        <ul class="navigation__list">
            <li><a class="navigation__list--about-me" href="#">about me</a></li>
            <li>
                <a class="navigation__list--developer" href="#">developer</a>
            </li>
            <li><a class="navigation__list--musician" href="#">musician</a></li>
            <li>
                <a class="navigation__list--contact-me" href="#">contact me</a>
            </li>
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
            transition: color 0.4s;
        }

        .navigation__list--about-me {
            &:hover {
                color: $color1;
            }
        }
        .navigation__list--developer {
            &:hover {
                color: $color5;
            }
        }
        .navigation__list--musician {
            &:hover {
                color: $color4;
            }
        }
        .navigation__list--contact-me {
            &:hover {
                color: $color6;
            }
        }
    }
}
</style>
