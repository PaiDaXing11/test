<template>
  <dev>
    <h2>学生姓名：{{name}}</h2>
    <h2>学生年龄：{{age}}</h2>
  </dev>
</template>

<script>
export default {
  name: "Student",
  data(){
    return{
      name:'张',
      age:18
    }
  }
}
</script>
