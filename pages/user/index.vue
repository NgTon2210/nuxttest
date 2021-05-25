<template>
    <div>
        <h1>Nhap id</h1>
        <input type="text" v-model="userID">
        <button @click="showId">Click</button>
    </div>
</template>

<script>
    export default{
        data(){
            return{
                userID:'1'
            }
        },
        methods:{
            showId(){
                this.$router.push(`/user/${this.userID }`)
            }
        }
    }
</script>