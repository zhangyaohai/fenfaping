<template>
  <div class="personal-main">
<div class="personal-max">
     <div class="personal-name">
        <div class="weui-cell">
                <div class="weui-cell__hd"><label class="weui-label">原密码</label></div>
                <div class="weui-cell__bd">
                    <input class="weui-input" type="text" placeholder="请输入原密码"/>
                </div>
            </div>
       </div>
       <div class="personal-name">
        <div class="weui-cell">
                <div class="weui-cell__hd"><label class="weui-label">新密码</label></div>
                <div class="weui-cell__bd">
                    <input class="weui-input" type="text" placeholder="请输入新密码"/>
                </div>
            </div>
       </div>
        <div class="personal-name">
        <div class="weui-cell">
                <div class="weui-cell__hd"><label class="weui-label">确认密码</label></div>
                <div class="weui-cell__bd">
                    <input class="weui-input" type="text" placeholder="请确认密码"/>
                </div>
            </div>
       </div>
     <div class="personal-btn">
         <div class="weui-btn btn-new-true">保存</div>
     </div>
     </div>
  </div>
</template>
<script>
export default {};
</script>
<style scoped>
.personal-main {
  position: fixed;
  background: #fff;
  height: 100%;
  width: 100%;
}
.personal-max {
  width: 80%;
  margin: 0 auto;
  margin-top: 60px;
}


.image-mod {
  font-size: 16px;
  line-height: 40px;
  width: 100%;
}
.personal-name {
  width: 100%;
  border-bottom: 1px solid #f1f1f1;
}
.personal-btn {
  width: 100%;
  margin-top: 60px;
}
.btn-new-true {
  height: 50px;
  line-height: 50px;
  background: #000000;
  color: #fff;
  border-radius: 10px;
}
</style>
