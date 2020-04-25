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
    <div class="row">
      <DemoButton plain>普通按钮</DemoButton>
      <DemoButton type="primary" plain>主要按钮</DemoButton>
      <DemoButton type="success" plain>成功按钮</DemoButton>
      <DemoButton type="info" plain>提示按钮</DemoButton>
      <DemoButton type="danger" plain>危险按钮</DemoButton>
      <DemoButton type="warning" plain>警告按钮</DemoButton>
    </div>
    <div class="row">
      <DemoButton plain round>普通按钮</DemoButton>
      <DemoButton type="primary" plain round>主要按钮</DemoButton>
      <DemoButton type="success" plain round>成功按钮</DemoButton>
      <DemoButton type="info" plain round>提示按钮</DemoButton>
      <DemoButton type="danger" plain round>危险按钮</DemoButton>
      <DemoButton type="warning" plain round>警告按钮</DemoButton>
    </div>
    <div class="row">
      <DemoButton plain round circle>按</DemoButton>
      <DemoButton type="primary" plain round circle>按</DemoButton>
      <DemoButton type="success" plain round circle>按</DemoButton>
      <DemoButton type="info" plain round circle>按</DemoButton>
      <DemoButton type="danger" plain round circle>按</DemoButton>
      <DemoButton type="warning" plain round circle>按</DemoButton>
    </div>
    <div class="row">
      <DemoButton plain round circle disabled>按</DemoButton>
      <DemoButton type="primary" plain round circle disabled>按</DemoButton>
      <DemoButton type="success" plain round circle disabled>按</DemoButton>
      <DemoButton type="info" plain round circle disabled>按</DemoButton>
      <DemoButton type="danger" plain round circle disabled>按</DemoButton>
      <DemoButton type="warning" plain round circle disabled>按</DemoButton>
    </div>
    <div class="row">
      <DemoButton plain round circle icon="shoucang"></DemoButton>
      <DemoButton type="primary" plain round circle icon="wenjian"></DemoButton>
      <DemoButton type="success" plain round circle icon="gonglve"></DemoButton>
      <DemoButton type="info" plain round circle icon="yinhang"></DemoButton>
      <DemoButton type="danger" plain round circle icon="shanchu"></DemoButton>
      <DemoButton type="warning" plain round circle icon="lingsheng"></DemoButton>
    </div>
    <div class="row">
      <DemoButton type="primary" plain round @click="showMessage">提示按钮</DemoButton>
    </div>
  </div>
</template>

<script>

export default {
  name: 'App',
  methods: {
    showMessage () {
      alert('显示提示信息！！!')
    }
  }
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
  .row{
    margin-bottom: 25px;
  }
</style>
