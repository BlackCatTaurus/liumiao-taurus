<template>
<div id="app">
    <div class="l_building">
        <img src="./assets/logo_400x400.png" alt="thisIsMyLogo">
        <i class="fa fa-spinner fa-pulse fa-3x fa-fw"></i>
        <p>喵～网站正在建设中～123不久将上线第一版～敬请期待>_<</p>
    </div>
</div>
</template>

<script>

import Lib from 'assets/js/Lib';

export default {
  data() {
    return {

    }
  }
}

console.log('一入前端深似海，头发从此是路人 >_<|||  liumiao_taurus@163.com 欢迎交流～')
</script>

<style>
	html,body,#app{width:100%;height:100%;background: #2D3032;overflow: hidden;}
	.l_building{width: 50%;height: 50%;margin: 15% 25% 25%;text-align: center;}
    .l_building>img{height: 50%;margin: 0 auto}
    .l_building>i{color: #35dedf;  display: block;  margin: 5% auto;font-size: .8em;}
    .l_building>p{color: #35dedf;font-size: .8em;}

</style>
