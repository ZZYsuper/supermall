<template>
  <div class="top">
    <label>
      <input type="checkbox">全选
    </label>
    <p>商品</p>
    <p>单价</p>
    <p>数量</p>
    <p>小计</p>
    <p>操作</p>
  </div>
</template>

<script>
export default {
  name: 'top'
}
</script>

<style scoped lang="scss">
.top{
  width: 100%;
  height: 49px;
  background-color: #000000;
  display: flex;
  align-items: center;
  justify-content: space-between;
  color: #ffffff;
}
.top>p{
  width: 200px;
  text-align: center;
}
.top>p:nth-child(2){
  width: 400px;
}
.top>label{
  width: 200px;
  text-align: center;
}
</style>
