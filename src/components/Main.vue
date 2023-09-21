<script setup>
    import FirstIndex from './Main/FirstIndex.vue';
    import SecondIndex from './Main/SecondIndex.vue';
    import ThirdIndex from './Main/ThirdIndex.vue';
    import FourthIndex from './Main/FourthIndex.vue';
    import FifthIndex from './Main/FifthIndex.vue';
    import SixthIndex from './Main/SixthIndex.vue';
    import SeventhIndex from './Main/SeventhIndex.vue';
    import Footer from '../components/Footer.vue';
</script>

<template>
    <div class="mainContainer">
        <FirstIndex class="scrollSnap"></FirstIndex>
        <SecondIndex class="scrollSnap"></SecondIndex>
        <ThirdIndex class="scrollSnap"></ThirdIndex>
        <FourthIndex class="scrollSnap"></FourthIndex>
        <FifthIndex class="scrollSnap"></FifthIndex>
        <SixthIndex class="scrollSnap"></SixthIndex>
        <SeventhIndex class="scrollSnap"></SeventhIndex>
        <Footer class="scrollSnap"></Footer>
    </div>
</template>


<style>
.mainContainer {
    scroll-snap-type: y mandatory;
    /* scroll-margin-top: 10px; */
    height: 100vh;
    overflow: auto;
}
.scrollSnap {
    scroll-snap-align: center;
}
::-webkit-scrollbar {
    width: 8px;
    height: 8px;
    background-color: rgba(0, 0, 0, .1);
}

::-webkit-scrollbar-track {
    -webkit-box-shadow: inset 0 0 6px rgba(0, 0, 0, 0.1);
    border-radius: 10px;
    background-color: #F5F5F5;
}
::-webkit-scrollbar-thumb {
    border-radius: 10px;
    -webkit-box-shadow: inset 0 0 6px rgba(0, 0, 0, .1);
    background-color: #b3b3b3;
}
</style>