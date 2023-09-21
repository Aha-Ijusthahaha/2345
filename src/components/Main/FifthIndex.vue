<template>
    <div class="fifthIndex">
        <span class="fifthIndexTitle">多样皮肤 个性定制</span>
        <span class="fifthIndexSubTitle">我们提供多样皮肤，支持一键切换全面屏模式，同时也支持个性化定制皮肤，让您的浏览器更符合自己的喜好。</span>
        <a class="fifthIndexDownload" href="https://dl.2345.cc/2345explorer/2345Explorer_Setup_V11.6.exe">官方下载</a>
        <div class="fifthIndexImg"></div>
    </div>
</template>

<script setup>
</script>

<style scoped>
.fifthIndex {
    padding-top: 80px;
    height: 100vh;
    width: 100%;
    text-align: center;
}
.fifthIndexTitle {
    margin-top: 16px;
    display: block;
    font-size: 52px;
    font-weight: bold;
    color: #000;
    line-height: 69px;
    letter-spacing: 4px;
}
.fifthIndexSubTitle {
    display: block;
    font-size: 18px;
    color: #666;
    line-height: 24px;
    margin-top: 16px;
}
.fifthIndexDownload {
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
.fifthIndexDownload::after {
    content: url('https://ie.2345.cc/assets/v7/images/index_v2/btn_go_white.png');
    margin-left: 8px;
}
.fifthIndexImg {
    background-image: url('https://ie.2345.cc/assets/v7/images/index_v2/features_three_img.png');
    background-repeat: no-repeat;
    width: 100%;
    height: 100%;
    background-position: top;
}
</style>