<template>
  <div class="personal-main">
<div class="personal-max">
    
       <div class="personal-name">
        <div class="weui-cell">
                <div class="weui-cell__hd"><label class="weui-label">姓名</label></div>
                <div class="weui-cell__bd">
                    <input class="weui-input" type="text" placeholder="请输入姓名"/>
                </div>
            </div>
       </div>
       <div class="personal-name">
        <div class="weui-cell">
                <div class="weui-cell__hd"><label class="weui-label">联系方式</label></div>
                <div class="weui-cell__bd">
                    <input class="weui-input" type="text" placeholder="请输入联系方式"/>
                </div>
            </div>
       </div>
         <div class="personal-name">
        <div class="weui-cell">
                <div class="weui-cell__hd"><label class="weui-label">常驻地址</label></div>
                <div class="weui-cell__bd">
                    <input class="weui-input" type="text" placeholder="请输入常驻地址"/>
                </div>
            </div>
       </div>
        <div class="personal-name">
        <div class="weui-cell">
                <div class="weui-cell__hd"><label class="weui-label">支付宝号</label></div>
                <div class="weui-cell__bd">
                    <input class="weui-input" type="text" placeholder="请输入支付宝号"/>
                </div>
            </div>
       </div>

    <div class="certification-header"> 
          <div class="cation-title">上传营业执照</div>
          <div class="cation-push">
            <div class="cation-push-img picg">
              <img src="/static/images/android/drawable-mdpi/pic.png" alt="">
            </div>
             <div class="cation-push-img addg">
              <img src="/static/images/android/drawable-mdpi/add.png" alt="">
            </div>
          </div>
    </div>

     <div class="personal-btn">
         <div class="weui-btn btn-new-true">认证申请</div>
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
.cation-title{
  margin-top: 10px;
  line-height: 30px;
  width: 100%;
  padding-left: 10px;
}
.cation-push{
  height: 70px;
  margin-top: 10px;
}
.cation-push-img {
  margin-top: 5px;
  float: left;
}
.picg,.addg{
  margin-left: 10px;
}

</style>
