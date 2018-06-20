<template>
  <div>
      <ul>
        <li v-for="(item,indx) in home" :key="indx">{{ item }}</li>
      </ul>
  </div>
</template>

<script>
export default {
  data(){
    return{
      home:['home1','home2','home3','home4','home5']
    }
  }
};
</script>

<style scoped>
  ul,li{
    list-style-type: lower-roman;
  }
</style>