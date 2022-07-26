<template>
<div>
    <h1>Ref in Vue js 3</h1>
    <input type="text" ref="input" />
    <!--"input name could be anything" .is ref ke pass pure input field ka control aa gaya hai .whatever value u want  get or set osr style you can do it using ref-->
    <button v-on:click="getData">CLICK ME!!!</button>
</div>
</template>

<script>
export default {
    name: 'hRef',
    methods: {
        getData() {
            this.$refs.input.focus()
            let val=this.$refs.input.value;
            console.warn(val)
            this.$refs.input.style.color="red"

        }
    }
}
</script>

<style scoped>
h1 {
    color: cadetblue
}
</style>
