<template>
<h1>For Loop in vue.js</h1>
<ul>
    <li v-for="item in avenger" :key="item">{{item}}</li> <!-- v-for is for vue js for loop-->
</ul>
<br/>
<br/>
<ul>
    <li v-for="item in user" :key="item.email">
     Name is:{{item.name}}  And  Email is:{{item.email}}
    </li>
</ul>
</template>

<script>
export default {
    name: 'vFor',
    data() {
        return {
            avenger: ['thor', 'ironman', 'captain america', 'hulk'],
            user:[{name:"vishal",
            email:'vishal@error.com'},
            {name:"prathmesh",
            email:'prathmesh@pool.com'},
            {name:"ankita",
            email:'ankita@topper.com'},
            {name:"swapnil",
            email:'swapnil@ushar.com'}] //this is called as array of object
        }
    }
}
</script>

<style>
h1 {
    color: darkturquoise
}
</style>
