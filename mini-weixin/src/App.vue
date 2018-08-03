<template>
  <div id="app">
    
    <router-view/>
    <mu-container>
      <mu-bottom-nav>
      <mu-bottom-nav-item title="微信" icon="chat"></mu-bottom-nav-item>
      <mu-bottom-nav-item title="通讯录" icon="contacts"></mu-bottom-nav-item>
      <mu-bottom-nav-item title="发现" icon="explore"></mu-bottom-nav-item>
      <mu-bottom-nav-item title="我" icon="perm_identity"></mu-bottom-nav-item>
      </mu-bottom-nav>
      
      
    </mu-container>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
@import url("//unpkg.com/muse-ui@3.0.0-rc.7/dist/muse-ui.css");
#app {
  position: absolute;
  bottom: 0;
  right: 0;
  width:100%;
}
</style>
