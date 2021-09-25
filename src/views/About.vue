<template>
  <div class="about">
    <h1>This is an about page</h1>
  </div>
</template>
<script>
// import axios from 'axios'
export default {
  created(){
    this.$axios({
      method:'get',
      url:'index/ding.json',
    }).then((data)=>{
      console.log(data)
    })
  }
}
</script>
