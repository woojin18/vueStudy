<template>
  <div>
      <h1>This is homepage</h1>
      <!-- <coder name="Homewoojin"/> -->
      <form action="">
        <label for="">Name</label>
        <input type="text" v-model="name">
      </form>



      <p>{{name}}</p>
  </div>
</template>

<script>

/* import coder from '@/components/coder.vue'; */

export default {
  /* components:{
    coder
  }, */

  data(){
    return{
      name: ''
    }
  }

}
</script>

<style scoped>
h1{
  color: red;
}

</style>
