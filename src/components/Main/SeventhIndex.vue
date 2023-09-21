<template>
    <div class="seventhIndex">
        <span class="seventhIndexTitle">安全无忧 私密尊享</span>
        <span class="seventhIndexSubTitle">加强了隐私保护功能，有效阻止恶意网站对个人信息的窃取，您的隐私将得到最大程度的保护。</span>
        <a class="seventhIndexDownload" href="https://dl.2345.cc/2345explorer/2345Explorer_Setup_V11.6.exe">官方下载</a>
        <div class="seventhIndexImg"></div>
    </div>
</template>

<script setup>
</script>

<style scoped>
.seventhIndex {
    padding-top: 80px;
    height: 100vh;
    width: 100%;
    text-align: center;
}
.seventhIndexTitle {
    margin-top: 16px;
    display: block;
    font-size: 52px;
    font-weight: bold;
    color: #000;
    line-height: 69px;
    letter-spacing: 4px;
}
.seventhIndexSubTitle {
    display: block;
    font-size: 18px;
    color: #666;
    line-height: 24px;
    margin-top: 16px;
}
.seventhIndexDownload {
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
.seventhIndexDownload::after {
    content: url('https://ie.2345.cc/assets/v7/images/index_v2/btn_go_white.png');
    margin-left: 8px;
}
.seventhIndexImg {
    background-image: url('https://ie.2345.cc/assets/v7/images/index_v2/features_five_img.png');
    background-repeat: no-repeat;
    width: 100%;
    height: 100%;
    background-position: top;
    margin: 80px auto 0;
}
</style>