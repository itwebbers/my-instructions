<template>
  <div id="app">
    <!-- <h1>雾化宝的正确打开方式</h1> -->
    <div class="page__hd">
        <h1 class="page__title">雾化宝的正确打开方式</h1>
        <p class="page__desc">
          <span id="copyright_logo" class="rich_media_meta meta_original_tag">原创</span>
          呼吸卫士我的卫士
          </p>
    </div>
    <DbbVideo />
    <div class="z_concat">
      <p>
        <span>平台链接：</span>
        <i>http://opp.aslk.me:8099/statics/login.jsp</i>
      </p>
      <p>
        <span>平台支持热线：</span>
        <i>010-53352331</i>
      </p>
      <p>
        <span>平台支持热线：</span>
        <i>热线服务时间：周一至周五9:00---18:00</i>
      </p>
    </div>
    <router-view/>
    <div class="weui-footer">
        <p class="weui-footer__links">
            <a href="javascript:void(0);" class="weui-footer__link">康联畅享</a>
        </p>
        <p class="weui-footer__text">Copyright &copy; 2014-2018 huxiweishi.com</p>
    </div>
  </div>
</template>

<script>
  import DbbVideo from './components/dbbVideo'
  export default {
    name: 'app',
    components: {
      DbbVideo
    },
    data() {
      return {

      }
    }
  }

</script>

<style>
  #app {
    width: 100%;
    font-size: .28rem;
    color: #666;
  }

  .meta_original_tag {
    display: inline-block;
    vertical-align: middle;
    padding: 1px .5em;
    border: 1px solid #9e9e9e;
    color: #8c8c8c;
    border-top-left-radius: 20% 50%;
    -moz-border-radius-topleft: 20% 50%;
    -webkit-border-top-left-radius: 20% 50%;
    border-top-right-radius: 20% 50%;
    -moz-border-radius-topright: 20% 50%;
    -webkit-border-top-right-radius: 20% 50%;
    border-bottom-left-radius: 20% 50%;
    -moz-border-radius-bottomleft: 20% 50%;
    -webkit-border-bottom-left-radius: 20% 50%;
    border-bottom-right-radius: 20% 50%;
    -moz-border-radius-bottomright: 20% 50%;
    -webkit-border-bottom-right-radius: 20% 50%;
    font-size: 15px;
    line-height: 1.1;
}
.rich_media_meta {
    display: inline-block;
    vertical-align: middle;
    margin-right: .08rem;
    margin-bottom: .1rem;
    font-size: .16rem;
    
}
.page__desc, .page__title {
  padding-left: .5rem;
}

  .z_concat i {
    font-style: normal;
    font-size: .26rem;
    color: #67C23A;
  }

  .z_concat p {
    font-size: .30rem;
    color: #5A5E66;
    text-align: left;
    padding-left: .5rem;
  }
.weui-footer {
  margin-top: 1rem;
}
.weui-footer p {
  font-size: .24rem;
}
.weui-footer a {
  font-size: .28rem;
}
</style>
