<template>
  <div id="login">
      <div class="login-wrap">
          <ul class="menu-tab">
              <li class="current">登录</li>
              <li>注册</li>
          </ul>
      </div>
  </div>
</template>
<script>

export default {
    name: 'login',
    data(){
        return {

        }
    },
    created(){},
    mounted(){},
    methods:{}
}
</script>
<style lang="scss" scoped>
 #login{
     background-color: blueviolet;
     height: 100vh;
 }
 .login-wrap{
     width: 330px;
     margin: auto;
 }
 .menu-tab{
     text-align: center;
     li{
         display: inline-block;
         width: 88px;
         line-height: 36px;
         font-size: 14px;
         color: #fff;
         border-radius: 2px;
     }
     .current{
         background-color: rgba($color: #000000, $alpha: 1.0);
     }
 }
</style>