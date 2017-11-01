<template>
  <header class="header">
      <div class="header-left icon-iconfontjiantouzuo iconfont"></div>
      <div class="header-title">
          输入城市/景点/游玩主题
      </div>
      <div class="header-right">
          北京
      </div>
      <i class="header-horn"></i>
  </header>
</template>

<script>
export default {
  
}
</script>

<style>
    @import "//at.alicdn.com/t/font_460484_o1xwiw4iyj02j4i.css";
    
    .header{
        height: .88rem;
        background: #00bcd4;
        position: relative;
    }

    .header-left{
        float: left;
        width: .4rem;
        padding: 0 .2rem;
        color: #fff;
        font-size: .4rem;
        line-height: .88rem;
    }

    .header-title{
        position: absolute;
        left: .8rem;
        right: 1.28rem;
        top: .14rem;
        line-height: .6rem;
        background: #fff;
        border-radius: .06rem;
        text-indent: .2rem;
        color: #ccc;
    }
    .header-right {
		float: right;
		width: 1.28rem;
		line-height: .88rem;
		text-align: center;
		color: #fff;
	}
    /*.header-right::after {
		content: "\0020";
		position: absolute;
		top: .2rem;
		right: 0;
		width: .2rem;
		height: .2rem;
		background: #fff;
        
	}*/
    .header-horn{
        width: 0;
        height:0;
        border-left:5px solid transparent;
        border-right: 5px solid transparent;
        border-top: 5px solid #fff;
        position: absolute; 
        top: .4rem;
        right: .1rem;
    }

</style>
