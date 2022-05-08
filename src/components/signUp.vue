<template>
    <div>
        <h1>c{{brand}}h1>
        <signIn v-on:changeName="updateName($event)"/>
    </div>
</template>
<script>
import signIn from "./signIn.vue"
export default {
    name:"signIn",
    components:{
        signIn
    },
    data()
    {
        return{
            brand:"hey dubai"
        }
    },
    methods:{
        
        updateName(user)
        {
           this.user=user
        }
    }

}
</script>