<template>
  <div class="home-page">
    <div class="card-list">
      <div class="card-item">1</div>
      <div class="card-item">2</div>
      <div class="card-item">3</div>
    </div>
    <Button type="primary">默认按钮</Button>
  </div>
</template>

<script>
import  {Button} from "vant";
export default {
  components: {
    Button
  }
};
</script>

<style type="text/css" lang="less">
.card-item {
  display: inline-block;
  width: 375/2px;
  height: 20px;
  vertical-align: top;
  margin-bottom: 10px;
  background: #f1f1f1;
  font-size: 14px;
}
</style>