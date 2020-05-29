<template>
  <div class="context">
    <div class="goods">
      <label>
        <input type="checkbox">
      </label>
      <div class="goodsImg">
        <img src="https://img13.360buyimg.com/n1/jfs/t1/107116/14/11184/94916/5e86fc51E37f85296/57e02c7c64cae28d.jpg" alt="">
      </div>
      <div class="goodsInfo">【女神礼物】迪奥口红烈艳蓝金唇膏女士999滋润888正红哑光520女生生日礼物礼品</div>
      <p class="goodsPrice">399.00</p>
      <div class="num">
        <button>-</button>
        <input type="text">
        <button>+</button>
      </div>
      <p class="subtotal">￥399.00</p>
      <p class="operation">删除</p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'context'
}
</script>

<style scoped lang="scss">
.goods{
  width: 100%;
  height: 107px;
  display: flex;
  background-color: #cccccc;
  align-items: center;
  background-color: #fff1dd;
}
.goods>label{
  width: 118px;
  margin: 10px;
  text-align: center;
}
.goods>.goodsImg{
  width: 60px;
  height: 60px;
}
.goods>.goodsImg>img{
  width: 100%;
  height: 100%;
}
.goods>.goodsInfo{
  width: 200px;
  font-size: 14px;
}
.goods>.goodsPrice{
  width: 200px;
  text-align: center;
}
.goods>.num{
  overflow: hidden;
  display: flex;
}
.goods>.num>button{
  width: 20px;
  height: 20px;
  border: 0;
}
.goods>.num>input{
  width: 40px;
}
.goods>.subtotal{
  width: 200px;
  text-align: center;
}
.goods>.operation{
  width: 86px;
  text-align: center
}
</style>
