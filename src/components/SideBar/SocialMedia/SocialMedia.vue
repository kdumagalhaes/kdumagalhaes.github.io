<template>
    <ul class="social-media">
        <li class="social-media__icon">
            <a href="https://github.com/kdumagalhaes" target="_blank">
                <img
                    src="@/assets/img/social-media-icons/github.svg"
                    alt="github"
                />
            </a>
        </li>
        <li class="social-media__icon">
            <a href="https://www.linkedin.com/in/kdumagalhaes/" target="_blank">
                <img
                    src="@/assets/img/social-media-icons/linkedin.svg"
                    alt="linkedin"
                />
            </a>
        </li>
        <li class="social-media__icon">
            <a href="https://www.instagram.com/kdumagalhaes/" target="_blank">
                <img
                    src="@/assets/img/social-media-icons/instagram.svg"
                    alt="instagram"
                />
            </a>
        </li>
        <li class="social-media__icon">
            <a href="https://twitter.com/kdumagalhaes" target="_blank">
                <img
                    src="@/assets/img/social-media-icons/twitter.svg"
                    alt="twitter"
                />
            </a>
        </li>
        <li class="social-media__icon">
            <a
                href="https://open.spotify.com/artist/7Kckvhfw7lWaH6ptEuneQv"
                target="_blank"
            >
                <img
                    src="@/assets/img/social-media-icons/spotify.svg"
                    alt="spotify"
                />
            </a>
        </li>
    </ul>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({})
</script>

<style scoped lang="scss">
.social-media {
    width: 100%;
    max-width: 200px;
    display: flex;
    justify-content: space-between;

    .social-media__icon {
        display: inline;

        img {
            width: 20px;
            transform: scale(1);
            transition: transform 0.3s;

            &:hover {
                transform: scale(1.3);
            }
        }
    }
}
</style>
