<script setup></script>

<template>
  <div class="footer">
    <div class="footerContainer">
      <div class="products">
        <span class="footerTitle">2345旗下产品</span>
        <div class="itemContainer">
          <a target="_blank" href="//www.2345.com/">2345网址导航</a>
          <a target="_blank" href="//ie.2345.cc/">2345加速浏览器</a>
          <a target="_blank" href="//safe.2345.cc/">2345安全卫士</a>
          <a target="_blank" href="//haozip.2345.cc/">2345好压</a>
          <a target="_blank" href="//pic.2345.cc/">2345看图王</a>
          <a target="_blank" href="//pinyin.2345.cc/">2345王牌输入法</a>
          <a target="_blank" href="//tianqi.2345.com/tianqiapp/">2345天气王</a>
          <a target="_blank" href="//app.2345.com/">2345手机浏览器</a>
          <a target="_blank" href="//zs.2345.com/">2345手机助手</a>
        </div>
      </div>
      <div class="about">
        <span class="footerTitle">关于我们</span>
        <div class="itemContainer">
          <a href="//ie.2345.cc/about.htm">关于2345加速浏览器</a>
          <a href="//union.2345.com/?2345ie">2345联盟</a>
          <a href="//ie.2345.cc/declare.htm">使用协议与隐私政策</a>
          <a href="//ie.2345.cc/link.htm" target="_blank">友情链接</a>
        </div>
      </div>
      <div class="contact">
        <span class="footerTitle">联系我们</span>
        <div class="itenContainer">
          <p class="displayText">
            <span
              >官方QQ:
              <a
                href="//wpa1.qq.com/IAjawi4S?_type=wpa&amp;qidian=true"
                target="_blank"
                >联系我们</a
              ></span
            >
          </p>
          <p class="displayText">
            客服电话: 4000002345 （工作日：09:00-18:00）
          </p>
          <p class="displayText">客服邮箱: kefu@2345.com</p>
          <p class="displayText">
            版权所有 <span>©</span> 2345&nbsp;
            <a href="//beian.miit.gov.cn" target="_blank"
              >沪ICP备15036234号-1</a
            >
          </p>
          <p class="displayText">
              <img src="//ie.2345.cc/img/beian.png" />
              沪公网安备31011502005439号
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
.footer {
  border-top: 1px solid #f2f2f2;
  width: 100%;
  height: 35vh;
  background: #f7f7f7;
  font-family: MicrosoftYaHei;
  padding: 27px 0;
}

.footerContainer {
  display: flex;
  height: 100%;
  width: 100%;
}

.products,
.about,
.contact {
  display: flex;
  height: 100%;
  flex-direction: column;
  padding: 0 58px;
}

.products {
  width: 0;
  flex-grow: 2;
  border-right: 1px solid rgba(0, 0, 0, 0.08);
}

.about {
  flex-grow: 1;
  width: 0;
  border-right: 1px solid rgba(0, 0, 0, 0.08);
}

.contact {
  width: 0;
  flex-grow: 1;
}

.footerTitle {
  display: inline-block;
  margin-bottom: 8px;
  font-size: 14px;
  font-weight: bold;
  color: #666;
}

.products .itemContainer {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
}

.about .itemContainer {
  display: grid;
  grid-template-columns: 1fr;
}

.contact .itemContainer {
  display: grid;
  grid-template-columns: 1fr;
}

a {
  line-height: 24px;
  color: #666;
  text-decoration: none;
}
.displayText {
  color: #666;
}
</style>
