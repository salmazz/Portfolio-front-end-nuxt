<template>
  <Row>
    <Col class="demo-spin-col" span="12">
      <Spin fix>
        <Icon type="ios-loading" size=18 class="demo-spin-icon-load"></Icon>
        <div>Loading</div>
      </Spin>
    </Col>
  </Row>
</template>
<script>
export default {

}
</script>
<style>
.demo-spin-col .circular {
  width:100px;
  height:100px;
}
.demo-spin-icon-load{
  animation: ani-demo-spin 1s linear infinite;
}
@keyframes ani-demo-spin {
  from { transform: rotate(0deg);}
  50%  { transform: rotate(180deg);}
  to   { transform: rotate(360deg);}
}
.demo-spin-col{
  height: 100px;
  position: relative;
}
.demo-spin-col {
  font-size: 25px;
}
</style>
