<template>
    <div class="firstIndex">
        <div class="firstIndexContainer">
            <div class="firstIndexText">
                <span class="textTitle">2345加速浏览器</span>
                <span class="textTitle2">全新升级</span>
            </div>
            <div class="firstIndexFeatures">
                <div class="firstIndexFeature">
                    <p class="primaryText">速度提升</p>
                    <p class="additionalText">Chromium97内核</p>
                </div>
                <div class="firstIndexFeature">
                    <p class="primaryText">更大空间</p>
                    <p class="additionalText">全新的界面设计</p>
                </div>
                <div class="firstIndexFeature">
                    <p class="primaryText">保护升级</p>
                    <p class="additionalText">更强的安全中心</p>
                </div>
                <div class="firstIndexFeature">
                    <p class="primaryText">效率提升</p>
                    <p class="additionalText">更多的便捷功能</p>
                </div>
            </div>
            <div class="firstIndexDownload">
                <a class="downloadBtn" href="https://dl.2345.cc/2345explorer/2345Explorer_Setup_V11.6.exe">官方下载</a>
                <p class="downloadTip1">版本V11.6<span>支持win7及以上系统</span></p>
                <a class="downloadTip2" href="https://dl.2345.cc/2345explorer/2345Explorer_Setup_V10.30.exe">XP系统用户请下载V10.30>></a>
            </div>

            
        </div>
    </div>
</template>

<script setup>
</script>

<style scoped>
@keyframes fadeIn {
    0%    { opacity: 0; }
    100%  { opacity: 1; }
}
.firstIndex {
    background: url('https://ie.2345.cc/assets/v7/images/index_v2/bg_home_1.png') no-repeat;
    background-position: top center;
    /* background-size: 1980px 620px; */
    background-size: cover;
    padding-top: 1px;
    height: calc(100vh + 100px);
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
}
.firstIndexContainer {
    transform: translateY(-100px);

}
.firstIndexText {
    line-height: 81px;
    animation: fadeIn 2s;
}
.textTitle {
    color: #222222;
}
.textTitle2 {
    background: linear-gradient(183deg, #327AFF 0%, #32CAFF 100%);
    -webkit-background-clip: text;
    background-clip: text;
    -webkit-text-fill-color: transparent;
}
.textTitle, .textTitle2 {
    font-size: 61px;
    font-weight: bold;
    line-height: 81px;
}
.firstIndexFeatures {
    display: flex;
    justify-content: center;
    align-items: center;
    margin-bottom: 30px;
}
.firstIndexFeature {
    width: 153px;
    border-right: 1px solid gray;
    /* margin-right: 60px; */
    text-align: center;
}
.firstIndexFeature .primaryText {
    font-size: 16px;
    font-weight: bold;
    color: #222;
    margin-bottom: 4px;
}
.firstIndexFeature .additionalText {
    font-size: 12px;
    color: #5C5C5C;
}
.firstIndexFeatures :nth-last-child(1) {
    border-right: none;
    /* margin-right: 0; */
}
.downloadBtn {
    display: block;
    width: 260px;
    height: 62px;
    background: #327AFF;
    border-radius: 4px;
    font-size: 22px;
    font-weight: bold;
    color: #FFFFFF;
    line-height: 62px;
    text-align: center;
    margin: 0 auto 0;
    cursor: pointer;
    text-decoration: none;
}
.downloadBtn::before {
    margin-right: 6px;
    position: relative;
    top: 1px;
    content: url('https://ie.2345.cc/assets/v7/images/index_v2/icon_download.png');
}
.downloadTip1, .downloadTip2 {
    text-align: center;
}
.downloadTip1 {
    color: #5C5C5C;
    margin: 4px auto;
}
.downloadTip1 span {
    margin-left: 8px;
}
.downloadTip2 {
    display: block;
    text-decoration: none;
    color: #1D73E8;
}
</style>