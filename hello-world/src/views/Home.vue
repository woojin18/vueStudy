<template>
  <div>
      <h1>This is homepage</h1>
      <!-- <coder name="Homewoojin"/> -->
      <form action="">
        <!-- <inputField :name="name" @update-name="updateName1"/> -->
        <inputField v-model="name"/>
        <br><button>Submit</button>
      </form>
      <p>{{name}}</p>
  </div>
</template>

<script>

/* import coder from '@/components/coder.vue'; */
import inputField from '@/components/inputField.vue';
export default {

  /* components:{
    coder
  }, */
  components:{
    inputField
  },

  data(){
    return{
      name: ''
    }
  },
  methods:{
    /* updateName1(name){
      this.name = name;
    } */
  }

}
</script>

<style scoped>
h1{
  color: red;
}

</style>
