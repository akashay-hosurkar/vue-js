<template>
<div>
    <h1>CSS BINDING</h1>
    <h2 :class="applyStyle">Class Binding</h2>
    <button v-on:click="colorfull=!colorfull">Apply Style</button> <!-- yaha se hum is true aur false kar rahe hai  -->
</div>
</template>

<script>
export default {
    name: 'classBinding',
    data() {
        return {
            colorfull: false
        }
    },
    computed: {
        applyStyle() {
            return {
                
                    green: this.colorfull,
                    err: true,
                    other:false
                    // other:true
                
            }
        }
    }
}
</script>

<style scoped>
h1 {
    color: orange
}

.green {
    background-color: aqua;
    width: 200px;
    padding: 10px;
}

.err {
    color: red;
}

.other {
    font-size: 50px;
}
</style>
