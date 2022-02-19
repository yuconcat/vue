<template>
    <div>
        <school></school>
        <Student></Student>
    </div>
</template>

<script>
    //引入组件
    import School from "./School.vue"
    import Student from "./Student.vue"
    export default {
        name: "app",
        components:{
            School:School,
            Student:Student
        }
    }
</script>

<style scoped>

</style>