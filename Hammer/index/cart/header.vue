<template>
        <div _ngcontent-c1="" class="title-bar"> <!----> <!----> <!----> <!----><h1 _ngcontent-c1="" class="nav-title"> 购物车 </h1> <!----> <!----><a _ngcontent-c1="" class="nav-edit">编辑</a> </div>
</template>

<script>
</script>

<style scoped>
    .title-bar[_ngcontent-c1] {
        background: #1d1d1d;
        background-image: linear-gradient(#1d1d1d,#181818);
        height: 50px;
        position: fixed;
        top: 0;
        left: 0;
        right: 0;
        z-index: 199;
        overflow: hidden;
    }
    .title-bar[_ngcontent-c1] .nav-title[_ngcontent-c1] {
        color: #fff;
        font-size: 18px;
        line-height: 20px;
        padding: 16px 0 0;
        text-align: center;
        position: absolute;
        top: 0;
        left: 60px;
        right: 60px;
        overflow: hidden;
        text-overflow: ellipsis;
        white-space: nowrap;
    }
    .title-bar[_ngcontent-c1] .nav-edit[_ngcontent-c1] {
        padding: 10px 13px 0;
        right: 6px;
    }
   .title-bar[_ngcontent-c1] .nav-edit[_ngcontent-c1] {
        background: #070707;
        background: linear-gradient(#131313,#070707);
        color: #fff;
        border-radius: 4px;
        box-sizing: border-box;
        font-size: 12px;
        height: 32px;
        line-height: 1;
        position: absolute;
        top: 50%;
        -webkit-transform: translateY(-50%);
        transform: translateY(-50%);
    }
</style>