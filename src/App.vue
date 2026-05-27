<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <el-button>Default</el-button>
  <el-button type="primary">Primary</el-button>
  <el-button type="success">Success</el-button>
  <el-button type="info">Info</el-button>
  <el-button type="warning">Warning</el-button>
  <el-button type="danger">Danger</el-button>
  <el-switch v-model="value1" />
  <el-switch v-model="value2" class="ml-2" style="--el-switch-on-color: #13ce66; --el-switch-off-color: #ff4949" />
</template>

<script>

export default {
  name: 'App',
  setup() {
    const value1 = ref(false)
    const value2 = ref(true)
    
     
    return{
      value1,
      value2
    }
  }

}
import { ref } from 'vue'


</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
