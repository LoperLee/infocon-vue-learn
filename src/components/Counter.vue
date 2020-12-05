<template>
  <div>
    <p>카운터! {{ cnt }}</p>
    <button @click="up">올리기</button>  
    <button @click="down">내리기</button>  
    <button @click="reset">초기화</button> 
  </div> 
 
</template>
<script>
export default {
    data() {
      return {
        cnt: 100
      }
    },
   
    methods: {
      up() {
        this.cnt++ 
    },
      down(){
      this.cnt--
    },  
     reset(){ 
     this.cnt=100
    }, 
  }
}
</script> 