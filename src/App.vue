<template>
  <div id="app">
    <Header></Header>
    <el-row :gutter="8">
      <el-col :span="3"><Nav></Nav></el-col>
      <el-col :span="21"><FirstTable></FirstTable></el-col>
    </el-row>
  </div>
</template>

<script>
import Header from './components/Header'
import Nav from './components/Nav'
import FirstTable from './components/FirstTable'

export default {
  components: {
    Header,
    Nav,
    FirstTable
  }
}
</script>

<style>
body {
  margin: 0px;
}

</style>
