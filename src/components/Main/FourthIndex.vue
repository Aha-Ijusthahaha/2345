<template>
    <div class="fourthIndex">
        <span class="fourthIndexTitle">免费翻译 无缝沟通</span>
        <span class="fourthIndexSubTitle">使用2345加速浏览器，您可以轻松应对各种语言场景，支持网页一键翻译和划词翻译，让您的沟通更加便捷无忧。</span>
        <a class="fourthIndexDownload" href="https://dl.2345.cc/2345explorer/2345Explorer_Setup_V11.6.exe">官方下载</a>
        <div class="fourthIndexImg"></div>
    </div>
</template>

<script setup>
</script>

<style scoped>
.fourthIndex {
    padding-top: 80px;
    height: 100vh;
    width: 100%;
    width: 100%;
    background: linear-gradient(180deg, #1064FF 0%, #61B2FF 100%);
    text-align: center;
}
.fourthIndexTitle {
    margin-top: 16px;
    display: block;
    font-size: 52px;
    font-weight: bold;
    color: #fff;
    line-height: 69px;
    letter-spacing: 4px;
}
.fourthIndexSubTitle {
    margin-top: 16px;
    display: block;
    font-size: 18px;
    color: #fff;
    line-height: 24px;
}
.fourthIndexDownload {
    display: block;
    width: 142px;
    height: 44px;
    background: #FFFFFF;
    border-radius: 22px;
    font-size: 16px;
    font-weight: bold;
    color: #327AFF;
    line-height: 44px;
    margin: 20px auto 0;
    cursor: pointer;
    text-decoration: none;
}
.fourthIndexDownload::after {
    content: url('https://ie.2345.cc/assets/v7/images/index_v2/btn_go_blue.png');
    margin-left: 8px;
}
.fourthIndexImg {
    background-image: url('https://ie.2345.cc/assets/v7/images/index_v2/features_two_img.png');
    background-repeat: no-repeat;
    width: 100%;
    height: 100%;
    background-position: top;
}
</style>