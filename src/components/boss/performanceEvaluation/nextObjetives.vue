<template>
    <form-next-objetives :onlyLecture="onlyLecture" />
</template>

<script>
import formNextObjetives from '@/components/boss/applyPerformanceEvaluations/formNextObjetives.vue';

export default {
    props: {
        onlyLecture: {
            type: Boolean,
            default: false,
        },
    },
    components: {
        formNextObjetives,
    },
};
</script>

<style scoped>

</style>
