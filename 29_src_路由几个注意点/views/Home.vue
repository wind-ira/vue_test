<template>
  <h2>我是Home的内容</h2>
</template>

<script>
  export default {
    name: 'Home',
    mounted(){
      console.log('Home组件被挂载了',this);
    },
    beforeDestroy(){
      console.log('Home组件被销毁了',this);
    }
  }
</script>

<style>

</style>