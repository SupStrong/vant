<template>
  <div id="commonNav" style="background-color: rgb(255, 255, 255)">
    <a
      id="mCommonHome"
      style="width: 20%"
      href="javascript:void(0)"
      class="J_ping"
      report-eventid="MCommonBottom_Home"
      ><div class="icon-center">
        <img
          class="nav-img"
          src="https://img11.360buyimg.com/jdphoto/s130x100_jfs/t1/67550/26/12426/5094/5d9c4b13Eea435a3f/81328b0609c60a3c.png"
        /></div></a
    ><a
      id="mCommonType"
      style="width: 20%"
      href="https://so.m.jd.com/category/all.html?searchFrom=home "
      class="J_ping"
      report-eventid="MCommonBottom_Category"
      ><div class="icon-center">
        <img
          class="nav-img"
          src="https://img11.360buyimg.com/jdphoto/s130x100_jfs/t1/56507/6/12787/3168/5d9c4b12Ef363dd8d/4af32f42575509d8.png"
        /></div></a
    ><a
      id="mCommonDiscover"
      style="width: 20%"
      href="https://wqs.jd.com/portal/wx/tuan/pingouv3.shtml?sceneval=2&amp;fromM=1&amp;ptag=138097.1.6"
      class="J_ping"
      report-eventid="MCommonBottom_Find"
      ><div class="icon-center">
        <img
          class="nav-img"
          src="https://img12.360buyimg.com/img/s130x100_jfs/t1/152922/39/13124/3525/5ff2ae9eE4a0a7636/a161ad4f4d2bb5ea.png "
        /></div></a
    ><a
      id="mCommonCart"
      style="width: 20%"
      href="https://p.m.jd.com/cart/cart.action?fromnav=1"
      class="J_ping"
      report-eventid="MCommonBottom_Cart"
      ><div class="icon-center">
        <img
          class="nav-img"
          src="https://img11.360buyimg.com/jdphoto/s130x100_jfs/t1/64954/4/12406/3529/5d9c4b12Ee7a82735/f2fe0a88bf344736.png"
        /></div></a
    ><a
      id=""
      style="width: 20%"
      href="https://home.m.jd.com/myJd/newhome.action"
      class="J_ping"
      report-eventid="MCommonBottom_NotLogin"
      ><div class="icon-center">
        <img
          class="nav-img"
          src="https://img11.360buyimg.com/jdphoto/s130x100_jfs/t1/68400/36/12368/3153/5d9c4b13E0e0d80a8/876c40f17d91ce44.png"
        /></div
    ></a>
  </div>
</template>

<script>
export default {
  name: "FooterMenu",
  setup() {},
};
</script>

<style lang="less" scoped>
#commonNav {
  margin: 0;
  padding: 0;
  position: fixed;
  left: 0;
  bottom: 0;
  z-index: 31;
  box-sizing: border-box;
  width: 100%;
  list-style: none;
  background-color: #fff;
  box-shadow: 0 0 10px 0 hsla(0, 6%, 58%, 0.6);
  -webkit-box-shadow: 0 0 10px 0 hsla(0, 6%, 58%, 0.6);
  -moz-box-shadow: 0 0 10px 0 hsla(0, 6%, 58%, 0.6);
  font-size: 16px;
}
#commonNav > a {
  position: relative;
  width: 20%;
  height: 60px;
  box-sizing: border-box;
  float: left;
  font-size: 16px;
  background-color: transparent;
  text-align: center;
}
#commonNav .nav-img {
  vertical-align: bottom;
}
#commonNav .icon-center img {
  z-index: 1;
  width: 100%;
}
</style>
