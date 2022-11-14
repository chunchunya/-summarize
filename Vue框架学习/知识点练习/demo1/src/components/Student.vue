<template>
  <div class="student">
    <h2>学生名称：{{name}}</h2>
    <h2>学生性别：{{sex}}</h2>
  </div>
</template>

<script>
export default {
  name: 'Student',
  data(){
    return{
      name:'小张同志',
      sex:'女'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.student{
  background-color:rgb(184, 118, 197);
}
</style>
