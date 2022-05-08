<template>
    <div>
        <h1>Welcome to Vue js components</h1>
       <h1>{{data}}</h1>
       <h1>{{msg}}</h1>
       
    </div>
</template>

<script>
export default {
    name:'HomeVue',
    props:{
        data:String,
        msg:String
    }
}
</script>