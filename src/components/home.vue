<template>
  <div class="z_contanier">
    <article class="weui-article">
      <section>
        <section>
          <h3>产品简介</h3>
          <p>
            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;雾化宝是一款采用无线传输技术（GPRS）， 用于监控各家庭台式雾化机使用时间的智能插座， 并将雾化机的开机时间和关机时间发送至数据管理平台的产品。
          </p>
        </section>
      </section>
    </article>
    <div class="weui-panel weui-panel_access">
      <!-- <div class="weui-panel__hd">文字组合列表</div> -->
      <div class="weui-panel__bd">
        <div class="weui-media-box weui-media-box_text">
          <h3 class="weui-media-box__title">产品包含</h3>
          <p class="weui-media-box__desc z_all_have">雾化宝一台;</p>
          <p class="weui-media-box__desc z_all_have">保修卡一张</p>
          <p class="weui-media-box__desc z_all_have">使用手册一份</p>
          <p class="weui-media-box__desc z_all_have">合格证一张</p>
        </div>
      </div>
    </div>
    <article class="weui-article">
      <section>
        <section>
          <h3>设备部位图</h3>
          <p class="pro_data">
            <img :src="proData.chakong" alt="">
            <img :src="proData.keti" alt="">
          </p>
        </section>
      </section>
    </article>
    <div class="weui-panel weui-panel_access">
      <!-- <div class="weui-panel__hd">文字组合列表</div> -->
      <div class="weui-panel__bd">
        <div class="weui-media-box weui-media-box_text">
          <h3 class="weui-media-box__title">基本操作功能</h3>
          <p class="weui-media-box__desc">1. 准备好本产品与雾化机；</p>
          <p class="weui-media-box__desc">2. 将雾化机电源插头插入雾化宝电源插孔；</p>
          <p class="weui-media-box__desc">3. 将雾化宝插入市电的电源插座中；</p>
          <p class="weui-media-box__desc">4. 打开雾化机上的电源开关，进行雾化，LED指示灯变为红色；</p>
          <p class="weui-media-box__desc">5. 关闭雾化机上的电源开关，结束雾化；</p>
          <p class="weui-media-box__desc">6. 等待红色LED指示灯熄灭，完成整个操作过程；</p>
          <p class="weui-media-box__desc">7. 数据管理平台收到该次雾化机的开机时间与关机时间的数据；</p>
        </div>
        <div class="weui-media-box weui-media-box_text">
          <h3 class="weui-media-box__title">产品规格</h3>
          <table>
            <tbody>
              <tr class="">
                <td style="padding: 0px 7px;border-color: windowtext;" width="132" valign="top">
                  <p>
                    <strong>
                      <span style="font-size: 14px;">产品规格</span>
                    </strong>
                  </p>
                </td>
                <td style="padding: 0px 7px;border-left: medium none;border-color: windowtext windowtext windowtext currentcolor;" width="324"
                  valign="top">
                  <p>
                    <span style="font-size: 14px;">47.2mm X 55.7mm X 46.8mm</span>
                  </p>
                </td>
              </tr>
              <tr>
                <td style="padding: 0px 7px;border-color: currentcolor windowtext windowtext;border-top: medium none;" width="132" valign="top">
                  <p>
                    <strong>
                      <span style="font-size: 14px;">重量</span>
                    </strong>
                  </p>
                </td>
                <td style="padding: 0px 7px;border-left: medium none;border-color: currentcolor windowtext windowtext currentcolor;border-top: medium none;"
                  width="318" valign="top">
                  <p>
                    <span style="font-size: 14px;">60.0g</span>
                  </p>
                </td>
              </tr>
              <tr>
                <td style="padding: 0px 7px;border-color: currentcolor windowtext windowtext;border-top: medium none;" width="132" valign="top">
                  <p>
                    <strong>
                      <span style="font-size: 14px;">输入</span>
                    </strong>
                  </p>
                </td>
                <td style="padding: 0px 7px;border-left: medium none;border-color: currentcolor windowtext windowtext currentcolor;border-top: medium none;"
                  width="318" valign="top">
                  <p>
                    <span style="font-size: 14px;">220VAC，50/60Hz，Imax=2A</span>
                  </p>
                </td>
              </tr>
              <tr>
                <td style="padding: 0px 7px;border-color: currentcolor windowtext windowtext;border-top: medium none;" width="132" valign="top">
                  <p>
                    <strong>
                      <span style="font-size: 14px;">待机功耗</span>
                    </strong>
                  </p>
                </td>
                <td style="padding: 0px 7px;border-left: medium none;border-color: currentcolor windowtext windowtext currentcolor;border-top: medium none;"
                  width="324" valign="top">
                  <p>
                    <span style="font-size: 14px;">&lt;100mW</span>
                  </p>
                </td>
              </tr>
              <tr>
                <td style="padding: 0px 7px;border-color: currentcolor windowtext windowtext;border-top: medium none;" width="132" valign="top">
                  <p>
                    <strong>
                      <span style="font-size: 14px;">指示灯</span>
                    </strong>
                  </p>
                </td>
                <td style="padding: 0px 7px;border-left: medium none;border-color: currentcolor windowtext windowtext currentcolor;border-top: medium none;"
                  width="324" valign="top">
                  <p>
                    <span style="font-size: 14px;">红色LED</span>
                  </p>
                </td>
              </tr>
              <tr>
                <td style="padding: 0px 7px;border-color: currentcolor windowtext windowtext;border-top: medium none;" width="132" valign="top">
                  <p>
                    <strong>
                      <span style="font-size: 14px;">配套雾化机型号</span>
                    </strong>
                  </p>
                </td>
                <td style="padding: 0px 7px;border-left: medium none;border-color: currentcolor windowtext windowtext currentcolor;border-top: medium none;"
                  width="324" valign="top">
                  <p>
                    <span style="font-size: 14px;">NE-C25S/NE-C28/</span>
                  </p>
                </td>
              </tr>
              <tr>
                <td style="padding: 0px 7px;border-color: currentcolor windowtext windowtext;border-top: medium none;" width="132" valign="top">
                  <p>
                    <strong>
                      <span style="font-size: 14px;">操作环境</span>
                    </strong>
                  </p>
                </td>
                <td style="padding: 0px 7px;border-left: medium none;border-color: currentcolor windowtext windowtext currentcolor;border-top: medium none;"
                  width="324" valign="top">
                  <p>
                    <span style="font-size: 14px;">10—40℃，10—90%RH</span>
                  </p>
                </td>
              </tr>
              <tr>
                <td style="padding: 0px 7px;border-color: currentcolor windowtext windowtext;border-top: medium none;" width="132" valign="top">
                  <p>
                    <strong>
                      <span style="font-size: 14px;">存储环境</span>
                    </strong>
                  </p>
                </td>
                <td style="padding: 0px 7px;border-left: medium none;border-color: currentcolor windowtext windowtext currentcolor;border-top: medium none;"
                  width="324" valign="top">
                  <p>
                    <span style="font-size: 14px;">4—35℃，10—90%RH</span>
                  </p>
                </td>
              </tr>
              <tr>
                <td style="padding: 0px 7px;border-color: currentcolor windowtext windowtext;border-top: medium none;" width="132" valign="top">
                  <p>
                    <strong>
                      <span style="font-size: 14px;">频段</span>
                    </strong>
                  </p>
                </td>
                <td style="padding: 0px 7px;border-left: medium none;border-color: currentcolor windowtext windowtext currentcolor;border-top: medium none;"
                  width="324" valign="top">
                  <p>
                    <span style="font-size: 14px;">EGSM900，DCS1800</span>
                  </p>
                </td>
              </tr>
            </tbody>
          </table>
        </div>
        <div class="weui-media-box weui-media-box_text">
          <h3 class="weui-media-box__title z_test">指示灯状态与含义</h3>
          <table>
            <tbody>
              <tr class="">
                <td style="padding: 0px 7px;border-color: windowtext;" width="87" valign="top">
                  <p>
                    <strong>
                      <span style="font-size: 14px;">亮灯颜色</span>
                    </strong>
                  </p>
                </td>
                <td style="padding: 0px 7px;border-left: medium none;border-color: windowtext windowtext windowtext currentcolor;" width="76"
                  valign="top">
                  <p>
                    <strong>
                      <span style="font-size: 14px;">状态</span>
                    </strong>
                  </p>
                </td>
                <td style="padding: 0px 7px;border-left: medium none;border-color: windowtext windowtext windowtext currentcolor;" width="276"
                  valign="top">
                  <p>
                    <strong>
                      <span style="font-size: 14px;">含义</span>
                    </strong>
                  </p>
                </td>
              </tr>
              <tr>
                <td style="padding: 0px 7px;border-color: currentcolor windowtext windowtext;border-top: medium none;" width="87" valign="top">
                  <p>
                    <span style="font-size: 14px;">红灯</span>
                  </p>
                </td>
                <td style="padding: 0px 7px;border-left: medium none;border-color: currentcolor windowtext windowtext currentcolor;border-top: medium none;"
                  width="76" valign="top">
                  <p>
                    <span style="font-size: 14px;">常亮</span>
                  </p>
                </td>
                <td style="padding: 0px 7px;border-left: medium none;border-color: currentcolor windowtext windowtext currentcolor;border-top: medium none;"
                  width="270" valign="top">
                  <p>
                    <span style="font-size: 14px;">雾化宝工作中</span>
                  </p>
                </td>
              </tr>
              <tr>
                <td style="padding: 0px 7px;border-color: currentcolor windowtext windowtext;border-top: medium none;" width="87" valign="top">
                  <p>
                    <span style="font-size: 14px;">红灯</span>
                  </p>
                </td>
                <td style="padding: 0px 7px;border-left: medium none;border-color: currentcolor windowtext windowtext currentcolor;border-top: medium none;"
                  width="76" valign="top">
                  <p>
                    <span style="font-size: 14px;">闪烁</span>
                  </p>
                </td>
                <td style="padding: 0px 7px;border-left: medium none;border-color: currentcolor windowtext windowtext currentcolor;border-top: medium none;"
                  width="270" valign="top">
                  <p>
                    <span style="font-size: 14px;">因网络信号问题，数据上传失败</span>
                  </p>
                </td>
              </tr>
              <tr>
                <td style="padding: 0px 7px;border-color: currentcolor windowtext windowtext;border-top: medium none;" width="87" valign="top">
                  <p>
                    <span style="font-size: 14px;">熄灭</span>
                  </p>
                </td>
                <td style="padding: 0px 7px;border-left: medium none;border-color: currentcolor windowtext windowtext currentcolor;border-top: medium none;"
                  width="76" valign="top">
                  <br>
                </td>
                <td style="padding: 0px 7px;border-left: medium none;border-color: currentcolor windowtext windowtext currentcolor;border-top: medium none;"
                  width="276" valign="top">
                  <p>
                    <span style="font-size: 14px;">关机(雾化宝未插入电源插座)</span>
                  </p>
                  <p>
                    <span style="font-size: 14px;">带几张（雾化宝插入电源插座）</span>
                  </p>
                </td>
              </tr>
            </tbody>
          </table>
        </div>
        <div class="weui-panel__bd">
          <div class="weui-media-box weui-media-box_text">
            <h3 class="weui-media-box__title">注意事项</h3>
            <p class="weui-media-box__desc">请勿将雾化宝连接其他电器设备，只能连接雾化机使用；</p>
            <p class="weui-media-box__desc">请勿在雾化机工作时将雾化宝从电源插座上拔出；</p>
            <p class="weui-media-box__desc">请勿在高温、剧烈震动或电磁辐射环境下使用；</p>
            <p class="weui-media-box__desc">请勿私自拆卸，如遇问题请寻求专业人士的帮助；</p>
            <p class="weui-media-box__desc">请勿将本产品存放在过冷或过热的环境下；</p>
            <p class="weui-media-box__desc">请保持本产品干燥；</p>
            <p class="weui-media-box__desc">本产品无防水处理，请勿触碰水源或让任何液体流入机体内；</p>
          </div>
        </div>
        <div class="weui-panel__bd">
          <div class="weui-media-box weui-media-box_text">
            <h3 class="weui-media-box__title">注意事项</h3>
            <p class="weui-media-box__desc">清洁时请用70%酒精与干净抹布轻拭即可；</p>
            <p class="weui-media-box__desc">请勿将清洁液体流入机体内；</p>
            <p class="weui-media-box__desc">请勿将本产品泡在液体内；</p>
            <p class="weui-media-box__desc">请将本产品储存于室温下并避免阳光直晒与潮湿；</p>
          </div>
        </div>
        <div class="weui-panel__bd">
          <div class="weui-media-box weui-media-box_text">
            <h3 class="weui-media-box__title">产品保修条款</h3>
            <p class="weui-media-box__desc">本产品从购买之日起，凭保修卡享受一年免费保修。但不包含以下因使用者个人的原因而造成的故障，如：</p>
            <p class="weui-media-box__desc">a). 连接大功率电器设备，造成产品损坏（严禁雾化宝连接非雾化机的其他设备使用）。</p>
            <p class="weui-media-box__desc">b). 擅自拆装、改装该产品而造成的故障；</p>
            <p class="weui-media-box__desc">c). 在使用、搬运的过程中不慎跌落而造成的故障；</p>
            <p class="weui-media-box__desc">d). 因缺乏合理的使用而造成的故障；</p>
            <p class="weui-media-box__desc">e). 没有按照使用说明书的指示进行正确操作而造成的故障；</p>
            <p class="weui-media-box__desc">f). 因非授权的维修店的不当修理而造成的故障；</p>
            <p class="weui-media-box__desc">g). 对于自然灾害造成的产品损坏，如水灾、火灾、地震等自然灾害；</p>
          </div>
        </div>
        <div class="weui-panel__bd">
          <div class="weui-media-box weui-media-box_text">
            <h3 class="weui-media-box__title weui-media-box__title_01">FAQ</h3>
            <p class="weui-media-box__desc">1） Q：雾化机关机后，雾化宝长期插在电源插座上是否耗电？</p>
            <p class="weui-media-box__desc">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;A：雾化机关机后，雾化宝传输完数据后，LED灯熄灭，雾化机进入待机状态， 待机功耗
              <20mw，功耗极低，不存在耗电现象；</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    data() {
      return {
        proData: {
          chakong: require('./../assets/chakong.png'),
          keti: require('./../assets/keti.png')
        },
        useData: {
          proIntroduce: {

          }
        }
      }
    }
  }

</script>
<style lang="less">
  .z_contanier {
    padding: 0 .5rem;

    .text {
      font-size: .14;
    }

    .item {
      margin-bottom: .18px;
    }

    .clearfix:before,
    .clearfix:after {
      display: table;
      content: "";
    }

    .clearfix:after {
      clear: both
    }

    .box-card {
      width: 480px;
    }




    .weui-panel .weui-panel__bd .weui-media-box table {
      margin-bottom: 10px;
      border-collapse: collapse;
      display: table;
      width: 100%!important;
    }

    .weui-panel .weui-panel__bd .weui-media-box table td {
      padding: 0px .07px;
      /* border-color: windowtext;   */
      border: 1px solid #DDD;
    }

    .weui-panel .weui-panel__bd .weui-media-box table p {
      min-height: 2em;
      line-height: .6rem;
    }

    .weui-panel .weui-panel__bd .weui-media-box table td span {
      font-size: .28rem !important;
    }

    article.weui-article {
      font-size: .28rem;
      color: #3e3e3e;
    }

    .weui-article h3,
    .weui-media-box__title {
      font-size: .32rem;
      font-weight: bold;
      text-align: center;
      position: relative;
    }

    // .weui-article h3:before,
    // .weui-media-box__title:before {
    //   display: block;
    //   content: '';
    //   margin-right: auto;
    //   margin-left: auto;
    //   background-image: url("http://mmbiz.qpic.cn/mmbiz_png/fgnkxfGnnkRR2K0mLhmx9ZScsjl5n4LZkGyhVAF5zDZFY4ViceZ5dX3oTDRDjYAiakiap4xQBFuvAUM9aSZkSOjQw/0.png");
    //   background-size: auto .48rem;
    //   background-repeat: no-repeat;
    //   width: .6rem;
    //   height: .48rem;
    //   line-height: .54rem;
    //   text-align: left;
    //   color: rgb(255, 255, 255);
    //   box-sizing: border-box;
    //   position: absolute;
    //   top: 0;
    //   left: 30%;
    //   /* margin-left: -.3rem; */
    // }

    .z_all_have {
      padding-left: 2rem;
      line-height: .5rem;
    }

    .weui-media-box__desc {
      font-size: .28rem;
      line-height: .5rem;
      color: #3e3e3e;
      margin: 0 auto;
      /* text-align: center; */
    }

    .weui-article .pro_data {
      text-align: center;
      margin-top: .4rem;
    }

    .weui-media-box__title {
      margin-bottom: .4rem;
    }
    .weui-media-box__title_01 {
      text-align: left;
    }
    .weui-media-box__title_01:before {
      width: 0;
    }
    .z_test:before {
      margin-left: -6%;
    }
  }

</style>
