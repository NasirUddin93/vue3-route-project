<template>
    <div>
        <h1>Job Details page</h1>
        <p>The job is id {{id}}</p>
    </div>
</template>

<script>
export default {
    props:['id'],
    data() {
        return {
            id: this.$route.params.id,
        };
    },
    mounted() {
        
    },
    methods: {
        
    },
};
</script>

<style lang="scss" scoped>

</style>