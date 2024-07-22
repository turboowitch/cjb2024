<template>
  <div id="app">
    <el-menu router>
      <el-menu-item index="/menu-collects">Menu Collects</el-menu-item>
      <!-- 其他菜单项 -->
    </el-menu>
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App',
};
</script>

<style>
/* 样式 */
</style>
