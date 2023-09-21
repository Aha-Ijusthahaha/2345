<template>
    <div class="headerContainer">
        <a class='headerImage' href="//ie.2345.cc">
            <img class="headerLinkLogo" src="https://ie.2345.cc/assets/v7/pic/index/logo.png"/>
        </a>
        <div class="headerLinkContainer">
            <a href="//ie.2345.cc" style="color:#000; font-weight: bold;">首页</a>
            <a href="https://ixrygrfu1c2.feishu.cn/wiki/wikcnmYPV0YytEefeoIQ74F7RBm" style="color: #777;">帮助</a>
            <div class="headerSwitch">
                <a href="//ie.2345.cc" class="headerSwitchPC">电脑版</a>
                <a href="//app.2345.com" class="headerSwitchAPP">手机版</a>
            </div>
        </div>
    </div>
</template>

<script setup>
</script>

<style scoped>
.headerContainer {
    display: flex;
    align-items: center;
    height: 70px;
    width: 100%;
    background-color: #fff;
    justify-content: center;
}
.headerImage {
    display: flex;
    text-align: center;
    justify-content: center;
    flex-grow: 1;
}
.headerContainer a {
    font: 14px/1.5 microsoft yahei,Arial;
    text-decoration: none;
    margin-left: 24px;
}
.headerLinkContainer {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-grow: 1;
    height: 100%;
}
.headerSwitch {
    display: flex;
    font-size: 16px;
    height: 100%;
    justify-content: center;
    align-items: center;
}
.headerSwitchPC {
    color: #fff;
    padding-left: 16px;
    padding-right: 16px;
    padding-top: 8px;
    padding-bottom: 8px;
    background-color: #327AFF;
    border-radius: 20px;
}
.headerSwitchPC::before {
    content: '💻';
}
.headerSwitchAPP {
    color: #327AFF;
    background-color: #fff;
}
.headerSwitchAPP::before {
    content: '📱';
}
.headerSwitchPC:visited {
    color: #fff;
}
.headerSwitchAPP:visited {
    color: #327AFF;
}
</style>