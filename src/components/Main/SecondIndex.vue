<template>
    <div class="secondIndex">
        <div class="secondIndexItem">
            <a class="download-btn" href="https://dl.2345.cc/2345explorer/2345Explorer_Setup_V11.6.exe">
                <img src="https://ie.2345.cc/assets/v7/images/index_v2/subicon1.png">
                <div>无痕浏览></div>
            </a>
        </div>
        <div class="secondIndexItem">
            <a class="download-btn" href="https://dl.2345.cc/2345explorer/2345Explorer_Setup_V11.6.exe">
                <img src="https://ie.2345.cc/assets/v7/images/index_v2/subicon2.png">
                <div>鼠标手势></div>
            </a>
        </div>
        <div class="secondIndexItem">
            <a class="download-btn" href="https://dl.2345.cc/2345explorer/2345Explorer_Setup_V11.6.exe">
                <img src="https://ie.2345.cc/assets/v7/images/index_v2/subicon3.png">
                <div>超级拖拽></div>
            </a>
        </div>
        <div class="secondIndexItem">
            <a class="download-btn" href="https://dl.2345.cc/2345explorer/2345Explorer_Setup_V11.6.exe">
                <img src="https://ie.2345.cc/assets/v7/images/index_v2/subicon4.png">
                <div>PDF转化></div>
            </a>
        </div>
        <div class="secondIndexItem">
            <a class="download-btn" href="https://dl.2345.cc/2345explorer/2345Explorer_Setup_V11.6.exe">
                <img src="https://ie.2345.cc/assets/v7/images/index_v2/subicon5.png">
                <div>网页截图></div>
            </a>
        </div>
        <div class="secondIndexItem">
            <a class="download-btn" href="https://dl.2345.cc/2345explorer/2345Explorer_Setup_V11.6.exe">
                <img src="https://ie.2345.cc/assets/v7/images/index_v2/subicon6.png">
                <div>护眼模式></div>
            </a>
        </div>
        <div class="secondIndexItem">
            <a class="download-btn" href="https://dl.2345.cc/2345explorer/2345Explorer_Setup_V11.6.exe">
                <img src="https://ie.2345.cc/assets/v7/images/index_v2/subicon7.png">
                <div>账号管家></div>
            </a>
        </div>
        <div class="secondIndexItem">
            <a class="download-btn" href="https://dl.2345.cc/2345explorer/2345Explorer_Setup_V11.6.exe">
                <img src="https://ie.2345.cc/assets/v7/images/index_v2/subicon8.png">
                <div>划词工具></div>
            </a>
        </div>
    </div>
</template>

<script setup>
</script>

<style scoped>
.secondIndex {
    /* height: 100px; */
    display: flex;
    justify-content: space-evenly;
    align-items: center;
    flex-direction: row;
    transform: translateY(-20vh);
    /* border-radius: 16px 16px 0px 0px; */
    /* background: rgba(255,255,255,0.85); */
    padding: 22px 20px 0 40px;
    text-align: center;
}
.secondIndexItem {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    width: 100px;
    height: 104px;
    border-radius: 8px;
    background: rgba(255,255,255,0.8);
}
.secondIndexItem :hover {
    transform: translateY(-4px);
    background: rgba(255,255,255,0.6);
    box-shadow: 0px 4px 10px 0px rgb(231 240 255 / 50%);
    cursor: pointer;
    color: #327AFF;
    text-decoration: underline;
}
img {
    display: inline-block;
    width: 44px;
    height: 44px;
    margin-top: 4px;
    margin-bottom: 8px;
}
a {
    color: #666;
    text-decoration: none;
}
div {
    font: 14px microsoft yahei,Arial;
    text-align: center;
}
</style>