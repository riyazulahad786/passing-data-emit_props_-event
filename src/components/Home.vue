<template>
    <div>
        <h1>Home</h1>
        <User :getUser=" getUserName"/>
    </div>
</template>
<script>
import User from "./User.vue"
export default {
    // eslint-disable-next-line vue/multi-word-component-names
    name:"Home",
    components:{
        User
    },
    methods:{
        getUserName(name)
        {
            alert(name)
        }
    }
}
</script>