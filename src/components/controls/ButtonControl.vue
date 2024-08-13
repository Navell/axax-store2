<script lang='ts'>
    type Props = {
        text: string
    }

    defineProps<Props>()
</script>

<template>
    <button class="button"> 111 {{ text }}</button>
    
</template>

    <style scoped>
    .button {
        background-color: red;
    }
    </style>
    