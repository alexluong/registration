<template>
  <div id="app">
    <el-menu router theme="light" mode="horizontal">
      <el-menu-item index="/">Home</el-menu-item>
    </el-menu>
    <router-view />
  </div>
</template>

<script>
/*
 * Entry component for the app. Sets up base layout and navigation menu.
 */
export default {
  name: 'app',
};
</script>
