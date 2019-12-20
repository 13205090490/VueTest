
<template>
<div>
  <el-container style="height: 500px; border: 1px solid #eee">
    <el-radio v-model="radio" label="1">备选项</el-radio>
    <el-radio v-model="radio" label="2">备选项</el-radio>
  </el-container>
  <router-link :to="'/Login'">跳转到登录页面</router-link>
</div>
</template>

<style>
.el-header {
  background-color: #b3c0d1;
  color: #333;
  line-height: 60px;
}

.el-aside {
  color: #333;
}
</style>

<script>
export default {
  data() {
    return {
      radio:'1'
    };
  },
  mounted:function(){
    console.log(this.BASE_URL)
  }
};
</script>