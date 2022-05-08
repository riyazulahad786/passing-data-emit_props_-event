<template>
    <div>
        <h1>pass data parent to child comp</h1>
        <button v-on:click="upDateTitle">update</button>
    </div>
</template>
<script>
export default {
    // eslint-disable-next-line vue/multi-word-component-names
    name:"Child",
   methods:{
         upDateTitle()
    {
        this.$emit('changeTitle','data recieved from child updated')
    }
   }
   
} 
</script>