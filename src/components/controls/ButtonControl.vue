<script setup lang='ts'>
    type Props = {
        text: string
    }

    defineProps<Props>()
</script>

<template>
    <button class="button"> {{ text }}</button>
</template>


    