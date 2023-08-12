
<script setup>
import axios from 'axios';

const test = ()=>{
  axios.get(`http://10.169.141.43:8000/api/test`).then(
    (res) => {
      console.log(res.data)
    }
  )
}


</script>
<template>
  <div class="home">
    <button @click="test"> 
      click mo
    </button>
  </div>
</template>

