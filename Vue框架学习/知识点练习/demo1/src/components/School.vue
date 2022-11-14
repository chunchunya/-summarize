<template>
  <div class="school">
    <h2>学校名称：{{name}}</h2>
    <h2>学校地址：{{address}}</h2>
  </div>
</template>

<script>
import {Format,Validate} from "zhang-npm-utils"
export default {
  name: 'School',
  // data(){
  //   return{
  //     name:'广联达',
  //     address:'北京'
  //   }
  // },
  mounted(){
    this.format();
    this.validate();
  },
  methods:{
    format:function(){
      console.log(Format.formatMoney(123456789.123,'$',2));   
    },
    validate:function(){
      console.log(Validate.mobileCheck('123456'))
    }
  }
  
}


</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.school{
  background-color: aqua;
}
</style>
