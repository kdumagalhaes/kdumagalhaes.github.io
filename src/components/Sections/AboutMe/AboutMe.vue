<template>
    <div class="about-me">
        <span class="about-me__breadcrumb">/about me</span>
        <div class="flex">
            <img
                class="about-me__pic"
                src="@/assets/img/kadu.jpeg"
                alt="Kadu"
            />
            <div class="content">
                <h2 class="about-me__title">
                    Hi, I'm <strong>Carlos</strong>, <br />
                    but everyone calls me <strong>Kadu</strong>!
                </h2>
                <p class="about-me__paragraph">
                    I'm a technology, music and Tennis enthusiast! I like to
                    follow trends and know how things work.
                </p>
                <p class="about-me__paragraph">
                    I like to follow trends and know how things work. In my
                    professional journey, I have always been in direct contact
                    with customers and users of digital products, experiencing
                    their difficulties and needs up close. I now intend to start
                    another stage of my life working as a Front-end developer.
                    This choice is related to my fascination for the infinite
                    possibilities that web tools give us today, and my goal is
                    to contribute to having a more accessible web for everyone!
                </p>
            </div>
        </div>
    </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
    setup() {
        return {}
    },
})
</script>

<style scoped lang="scss">
.about-me {
    background-color: $color1;
    width: 100%;
    height: 100vh;
    padding: 80px;
    color: $color3;
    display: flex;
    flex-direction: column;

    .about-me__breadcrumb {
        margin-bottom: 40px;
    }

    .about-me__title {
        margin-bottom: 20px;
        font-size: 1.8rem;
        font-weight: $light;
    }

    .about-me__paragraph {
        margin-bottom: 20px;
        line-height: 20px;
        font-size: 1rem;
    }

    .flex {
        display: flex;
        align-items: center;
    }

    .about-me__pic {
        width: 300px;
        margin-right: 20px;
        box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1),
            0 10px 10px -5px rgba(0, 0, 0, 0.04);
    }
}
</style>
