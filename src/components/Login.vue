<template>
<!-- 整个页面 -->
  <div class="login_container">
    <!-- 白色盒子 -->
    <div class=box>
      <!-- 头像部分 -->
      <div class="avatar_box">
        <img src="../assets/logo.png" alt="">
      </div>
      <!-- 登陆表单区域 -->
      <el-form label-width="80px">
        <el-form-item label="活动名称">
          <el-input></el-input>
        </el-form-item>
      </el-form>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="less" scoped>
.login_container{
  background-color: #2b4b6b;
  height:100%;
}
.box{
  height:300px;
  width:450px;
  background-color: #fff;
  border-radius: 3px;
  // 让盒子水平居中
  position:absolute;
  left:50%;
  top:50%;
  transform: translate(-50%,-50%);

  // 嵌套
  .avatar_box{
    height: 130px;
    width: 130px;
    border :1px solid #eee;
    border-radius: 50%;
    padding:10px;
    box-shadow: 0 0 10px #ddd;
    position: absolute;
    left:50%;
    transform: translate(-50%,-50%);
    background-color: #fff;
    img{
      width: 100%;
      height: 100%;
      border-radius: 50%;
      background-color: #eee;
    }
  }
}
</style>
