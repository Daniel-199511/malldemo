<template>
  <div id="app">
    <router-view/>
    <!-- <div id="nav">
      <router-link to="/login">登录</router-link> |
      <router-link to="/register">注册</router-link>
    </div> -->
  </div>
</template>
<style lang="stylus">
#app
  font-family 'Avenir', Helvetica, Arial, sans-serif
  -webkit-font-smoothing antialiased
  -moz-osx-font-smoothing grayscale
  text-align center
  color #2c3e50

#nav
  a
    font-weight bold
    color #2c3e50
    &.router-link-exact-active
      color #42b983
</style>
