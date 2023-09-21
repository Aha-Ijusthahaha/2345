<template>
    <div class="thirdIndex">
        <span class="thirdIndexTitle">数据同步不丢失</span>
        <span class="thirdIndexSubTitle">个人收藏、账号密码在不同设备间轻松实现实时同步，告别繁琐操作，畅享随时随地的便捷浏览。</span>
        <a class="thirdIndexDownload" href="https://dl.2345.cc/2345explorer/2345Explorer_Setup_V11.6.exe">官方下载</a>
        <div class="thirdIndexImg"></div>
    </div>
</template>

<script setup>
</script>

<style scoped>
.thirdIndex {
    padding-top: 80px;
    height: 100vh;
    width: 100%;
    text-align: center;
}
.thirdIndexTitle {
    margin-top: 16px;
    display: block;
    font-size: 52px;
    font-weight: bold;
    color: #000;
    line-height: 69px;
    letter-spacing: 4px;
}
.thirdIndexSubTitle {
    display: block;
    font-size: 18px;
    color: #666;
    line-height: 24px;
    margin-top: 16px;
}
.thirdIndexDownload {
    display: block;
    width: 142px;
    height: 44px;
    background: #000;
    border-radius: 22px;
    font-size: 16px;
    font-weight: bold;
    color: #FFF;
    line-height: 44px;
    margin: 20px auto 0;
    cursor: pointer;
    text-decoration: none;
}
.thirdIndexDownload::after {
    content: url('https://ie.2345.cc/assets/v7/images/index_v2/btn_go_white.png');
    margin-left: 8px;
}
.thirdIndexImg {
    background-image: url('https://ie.2345.cc/assets/v7/images/index_v2/features-one-img.png');
    background-repeat: no-repeat;
    width: 100%;
    height: 100%;
    background-position: top;
}
</style>