<template>
    <form-competences :onlyLecture="onlyLecture" />
</template>

<script>
import formCompetences from '@/components/collaborator/applyPerformanceEvaluations/formCompetences.vue';

export default {
    props: {
        onlyLecture: {
            type: Boolean,
            default: false,
        },
    },
    components: {
        formCompetences,
    },
};
</script>

<style scoped>

</style>
