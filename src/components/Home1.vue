<template>
<h1>Two Way Binding</h1>
<input type="text" v-model="count" />
<h2>{{count}}</h2>
</template>

<script>
export default {
    name: 'twoBinding',
    data() {
        return {
            count:90
        }
    }
}
</script>

<style scoped>
h1{
    color: crimson;
}
h2{
    color: red;
}

