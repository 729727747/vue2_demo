<template>
    <div>
        <Student />
        <School />
    </div>

</template>

<script src="main.js"></script>
<script>
    import Student from './Student.vue'
    import School from './School.vue'

    export default {
        name:'App',
        components:{
            Student,
            School
        }
    }
</script>



