<template>
  <div id="app">
    <div class="row">
      <DemoButton>普通按钮</DemoButton>
      <DemoButton type="primary">主要按钮</DemoButton>
      <DemoButton type="success">成功按钮</DemoButton>
      <DemoButton type="info">提示按钮</DemoButton>
      <DemoButton type="danger">危险按钮</DemoButton>
      <DemoButton type="warning">警告按钮</DemoButton>
    </div>
  </div>
</template>

<script>

export default {
  name: 'App',
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
