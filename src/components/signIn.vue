<template>
    <div>
        <h1>pa</h1>
        <button v-on:click=" updateName">click</button>
    </div>
</template>
<script>
export default {
    name:"signIn",
    methods:{
        updateName()
        {
           this.$emit("changeName","keep doing work") 
        }
    }
}
</script>