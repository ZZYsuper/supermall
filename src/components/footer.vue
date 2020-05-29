<template>
  <div class="footer">
    <label>
      <input type="checkbox"> 全选
    </label>
    <p>删除所有商品</p>
    <p class="count">已选择 <span>22</span>商品</p>
    <p class="total">总价：9999</p>
    <a href="#">结算</a>
  </div>
</template>

<script>
export default {
  name: 'bottom'
}
</script>

<style scoped lang="scss">
.footer{
  margin-top: 5px;
  display: flex;
  height: 52px;
  width: 100%;
  align-items: center;
  border: 1px solid #5f5f5f;
  justify-content: space-between;
}
.footer>label{
  margin: 10px;
}
.footer>a{
  height: 100%;
  width: 94px;
  text-decoration: none;
  color: #000000;
  background-color: #ff0000;
  text-align: center;
  display: block;
  line-height: 52px;
  font-size: 18px;
}
.footer>.total,.footer>.count{
  width: 200px;
  text-align: center;
}
</style>
