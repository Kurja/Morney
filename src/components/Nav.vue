<template>
  <nav>
    <router-view></router-view>
    <div>
      <router-link to="/labels" class="item">
       <Icon name="label" />
        标签
      </router-link>
      <router-link to="/money" class="item">
        <Icon name="money"/>
        记账
      </router-link>
      <router-link to="/statistics" class="item">
        <Icon name="statistics" />
        统计
      </router-link>
    </div>
  </nav>
</template>

<script lang="ts">
// eslint-disable-next-line no-undef

  export default {
  name: 'Nav'
}
</script>

<style lang="scss" scoped>
nav {
  display: flex;
  box-shadow: 0 0 3px rgba(0,0,0,0.9) ;
  flex-direction: row ;
  //border: 1px solid black;

  > .item {
    //border: 1px solid green;
    width: 33.3333%;
    display: flex;
    justify-content: center;
    align-items: center;
  }
}
</style>