<template>
    <ul class="social-media">
        <li class="social-media__icon social-media__icon--github">
            <a href="" target="_blank">
                <img
                    src="@/assets/img/social-media-icons/github.svg"
                    alt="github"
                />
            </a>
        </li>
        <li class="social-media__icon social-media__icon--linkedin">
            <a href="" target="_blank">
                <img
                    src="@/assets/img/social-media-icons/linkedin.svg"
                    alt="linkedin"
                />
            </a>
        </li>
        <li class="social-media__icon social-media__icon--instagram">
            <a href="" target="_blank">
                <img
                    src="@/assets/img/social-media-icons/instagram.svg"
                    alt="instagram"
                />
            </a>
        </li>
        <li class="social-media__icon social-media__icon--twitter">
            <a href="" target="_blank">
                <img
                    src="@/assets/img/social-media-icons/twitter.svg"
                    alt="twitter"
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
        }
    }
}
</style>
