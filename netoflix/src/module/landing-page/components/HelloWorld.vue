<script setup lang="ts">

const { msg } = defineProps({
    msg: {
        type: String,
        required: true,
    },
});
</script>

<template>
    <div>
        {{ msg }}
    </div>
</template>

<style scoped>

</style>