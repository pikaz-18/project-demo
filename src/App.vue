<!--
 * @Author: zouzheng
 * @Date: 2020-06-08 17:08:55
 * @LastEditors: zouzheng
 * @LastEditTime: 2020-06-09 09:30:11
 * @Description: 这是XXX组件（页面）
--> 
<template>
  <div id="app">
    <excel-com></excel-com>
    <iframe-com></iframe-com>
  </div>
</template>

<script>
import { ExcelCom, IframeCom } from 'compoment-demo'
export default {
  name: 'App',
  components: {
    ExcelCom,
    IframeCom
  }
}
</script>

<style>
#app {
  display: flex;
  flex-direction: column;
}
</style>
