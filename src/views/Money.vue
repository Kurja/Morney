<template>
 <div>
   <Layout>
     <p>Money.vue</p>
   </Layout>
 </div>
</template>

<script lang="ts">
export default {
  name: 'Money',
}
</script>

<style lang="scss" scoped>
  .nav-wrapper{
    border:1px solid red;
    display: flex;
    flex-direction: column;
    height: 100vh;
  }
  .content{
    //border: 1px solid blue;
    overflow: auto;
    flex-grow: 1;
  }
</style>