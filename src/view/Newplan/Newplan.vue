<template>
  <div class="newplan">
    <p>推广目标：<button class="newplan-bg">网页</button><button>IOS应用</button><button>Android应用</button></p>
    <p>计划名称：<input type="text" placeholder="请设置广告名称"></p>
    <p>每日限额：<input type="text" placeholder="请设置每日限额"></p>
    <div class="newplan-btn">
      <button>下一步</button>
      <button>保存</button>
    </div>
  </div>
</template>

<script>
export default {
  name: 'newplan'
};
</script>

<style scoped>
  .newplan{
    margin-top: 25px;
  }
  .newplan p{
    color: rgb(94, 94, 94);
    font-size: 13px;
    margin-bottom: 15px;
  }
  .newplan p button{
    width: 90px;
    height: 30px;
    font-size: 12px;
    background: transparent;
    border: 1px solid #ccc;
  }
   .newplan .newplan-bg{
    background: #2873FF;
    color: #fff;
  }
  .newplan input{
    border: 1px solid #ccc;
    width: 330px;
    height: 28px;;
    color: #ccc;
  }
  .newplan-btn button{
    width: 130px;
    height: 40px;
    border: none;
    background: #ccc;
    color: #fff;
    margin-top: 30px;
  }
</style>
