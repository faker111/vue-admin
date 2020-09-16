<template>
  <div id="login">
    <font color="red">这里是登录页adasdas</font>
    <el-row>
      <el-button>默认按钮</el-button>
      <el-button type="primary">主要按钮</el-button>
      <el-button type="success">成功按钮</el-button>
      <el-button type="info">信息按钮</el-button>
      <el-button type="warning">警告按钮</el-button>
      <el-button type="danger">危险按钮</el-button>
    </el-row>
  </div>
</template>

<script>
export default {
  name: "login"
};
</script>



<style lang="scss" scoped>
#login {
  height: 100vh;
  background-color: #344a5f;
}
//scoped局部有效，不加全局有效
</style>



