<template>
<div>
    <h2>User Component</h2>
    <button v-on:click="getUser(userName)">Send User Name</button>
</div>
</template>

<script>
export default {
    name: 'userPage',
    data() {
        return {
            userName: "Bruce" //to use this in parent component we have to make function in hpage
        }
    },
    props:{
      getUser:Function //mere pass getUser function aane wali hai .its better to validate
    } //The alert function popping from our parent component that is hpage
}
</script>

<style>

</style>
