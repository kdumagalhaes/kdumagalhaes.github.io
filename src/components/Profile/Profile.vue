<template>
    <div class="profile">
        <img
            src="@/assets/img/profile-pic.png"
            alt="carlos pereira profile pic"
        />
        <div class="profile__divider">
            <h1>hi, I'm <strong>Kadu!</strong></h1>
            <p>
                {{ text }}
            </p>
        </div>
    </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
    props: {
        text: {
            type: String,
            required: true,
        },
    },
})
</script>

<style scoped lang="scss">
.profile {
    display: flex;
    align-items: center;

    img {
        margin-right: 15px;
    }

    h1 {
        font-size: 1.5rem;
        margin-bottom: 10px;
        font-weight: $light;
    }

    p {
        width: 100%;
        max-width: 220px;
        font-size: 0.8rem;
        line-height: 18px;
    }
}
</style>
