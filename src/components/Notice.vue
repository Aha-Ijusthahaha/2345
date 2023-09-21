<template>
    <div class="noticeContainer" v-if="showNotice">
        <span class="noticeText">温馨提示：您当前使用的浏览器不是2345加速浏览器，建议您下载最新版本2345加速浏览器</span>
        <a class="noticeLink" href="https://dl.2345.cc/2345explorer/2345Explorer_Setup_V11.6.exe">点击下载</a>
        <span class="noticeCloseEmoji" @click="setShowNotice"></span>
    </div>
</template>

<script setup>
import { ref } from 'vue';
let showNotice = ref(true)
let setShowNotice = function() {
    showNotice.value = false
}
</script>

<style scoped>
.noticeContainer {
    /* height: 28px; */
    width: 100%;
    background-color: #fff1d3;
    border-bottom: 1px solid #edbf9a;
    text-align: center;
}
.noticeText {
    color: #c4691f;
    line-height: 28px;
}
.noticeText::before {
    font-size: 16px;
    content: '📢 ';
}
.noticeLink {
    color: #da2128;
    margin-left: 5px;
}
.noticeCloseEmoji {
    line-height: 28px;
    float: right;
}
.noticeCloseEmoji::before {
    font-size: 16px;
    content: '❌';
    padding-right: 5px;
    cursor: pointer;
}
</style>