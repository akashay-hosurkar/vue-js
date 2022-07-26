<template>
<!-- <h1>Two Way Binding</h1>
<input type="text" v-model="count" />
<h2>{{count}}</h2> -->
<h1>Props in vue js</h1>
<studentCo :name="name" />
<teacherCo :name="name" />
</template>

<script>
import studentCo from './studentCo.vue'
import teacherCo from './teacherCo.vue'

export default {
    name: 'twoBinding',
    data() { // this data function is used for passing the same name
        return {
            name: "THOR" //here could be anything array object, string,function,integer,number we can transfer anything as props
        }
    },
    components: {
        studentCo,
        teacherCo
    }
    // data() {
    //     return {
    //         count:90
    //     }
    // }
}
</script>

<style scoped>
h1 {
    color: orange
}
</style>
