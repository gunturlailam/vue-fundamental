<script>
export default {
    data(){
        return{
            name:'Guntur Lailam Yuro'
        }
    },
    methods:{
        showName(){
            console.log(this.name)
        }
    }
}
</script>

<template>
    <h1>{{ name }}</h1>
</template>