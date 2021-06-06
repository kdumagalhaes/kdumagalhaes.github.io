<template>
    <div class="status">
        <ul class="status__list">
            <li>currently...</li>
            <li>
                working at
                <strong class="status__list--strong">{{ company }}</strong>
            </li>
            <li>
                learning
                <strong class="status__list--strong">{{ studying }}</strong>
            </li>
            <li>
                living in
                <strong class="status__list--strong">{{ country }}</strong>
            </li>
        </ul>
    </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
    props: {
        company: {
            type: String,
            required: true,
        },
        studying: {
            type: String,
            required: true,
        },
        country: {
            type: String,
            required: true,
        },
    },
})
</script>

<style scoped lang="scss">
.status {
    border-left: 3px solid $color1;
    padding-left: 10px;
    .status__list {
        line-height: 23px;

        .status__list--strong {
            color: $color1;
        }
    }
}
</style>
