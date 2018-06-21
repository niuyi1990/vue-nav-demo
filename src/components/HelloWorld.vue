<template>
  <div class="div_bac">

    <div class="div_title">用户登录</div>

    <div class="div_username">
      <input id="input_username" type="text" placeholder="请输入用户名"
             maxlength="15"
             onautocomplete="off"/>
    </div>

    <div class="div_password">
      <input id="input_password" type="text" placeholder="请输入密码"
             maxlength="15"
             onautocomplete="off"/>
    </div>

    <div class="div_login">登录</div>

  </div>
</template>

<script>
  export default {
    name: 'HelloWorld',
    data() {
      return {
        msg: 'Welcome to Your Vue.js App'
      }
    }
  }
</script>

<!--编写CSS样式-->
<style scoped>
  .div_bac {
    width: 100%;
    height: 100%;
  }

  .div_title {
    color: #ff0000;
    font-size: 20px;
  }

  .div_username {
    margin-top: 50px;
  }

  .div_login {
    background: #f45f63;
    color: #ffffff;
    margin-left: 20px;
    margin-right: 20px;
    padding-top: 10px;
    border-radius: 7px;
    padding-bottom: 10px;
    margin-top: 40px;
    opacity: 0.4;
  }
</style>
