<template>
    <div>
        <h1>{{title}}</h1>
        <p>{{name}}</p><br>
        <button @click="updateName">Change Name</button>
    </div>    
</template>


<script>
export default{
    props: {
        title: {
            type: String,
            default: 'defaultTitle'
        },
        name: {
            type: String,
            default: 'defaultName'
        }
    },
    data(){
        return{
            //name: 'coderwoojin',
        }
    },
    methods:{
        updateName(){
            this.name = 'coderwoojin Update';
        }
    }
}
</script>

<style scoped>

</style>
