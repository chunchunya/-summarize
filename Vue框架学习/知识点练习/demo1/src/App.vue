<template>
  <div>
    <h1 class="title">你好lala</h1>
    <School></School>
    <Student></Student>
  </div>
</template>

<script>

import School from './components/School.vue'
import Student from './components/Student.vue'
export default {
  name: 'App',
  components:{School,Student}
  
}
</script>

<style>
.title {
  color: brown;
}
</style>
