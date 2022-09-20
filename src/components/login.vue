<template>
    <div class="login">
      <div class="login_box">
        <div class="avatar">
          <img src="../assets/logo.png" alt="" />
        </div>
        <el-form label-width="80px">
          <el-form-item label="活动名称">
            <el-input v-model="form.name"></el-input>
          </el-form-item>
        </el-form>
      </div>
    </div>
  </template>
<script>
export default {
  name: 'Login'
}
</script>
<style lang="less" scoped>
  .login {
    background: #173a59;
    position: fixed;
    height: 100%;
    width: 100%;
    .login_box {
      background: #fff;
      width: 450px;
      height: 300px;
      border-radius: 3px;
      position: absolute;
      left: 50%;
      top: 50%;
      transform: translate(-50%, -50%);
      .avatar {
        width: 130px;
        height: 130px;
        border-radius: 50%;
        border: 1px solid #fff;
        padding: 10px;
        position: absolute;
        margin-left: 50%;
        transform: translate(-50%, -50%);
        box-shadow: 0 0 10px #999;
        img {
          background-color: #ccc;
          width: 100%;
          height: 100%;
          border-radius: 50%;
        }
      }
    }
  }
  </style>
