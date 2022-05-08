<template>
    <div>
        <h1>user</h1>
        <button v-on:click="getUser( userName)">SEND DATA</button>
    </div>
</template>
<script>
export default {
    // eslint-disable-next-line vue/multi-word-component-names
    name:"User",
    data(){
        return{
            userName:"dubai"
        }
    },
    props:{
        getUser:Function
    }
}
</script>