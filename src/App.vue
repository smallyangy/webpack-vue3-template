<template>
    <div>
        {{ str }}
    </div>
</template>

<script lang="ts">
import { defineComponent, ref } from 'vue';

export default defineComponent({
    name: 'App',
    setup() {
        const str = ref('hello');

        return {
            str
        };
    }
});
</script>

<style></style>
