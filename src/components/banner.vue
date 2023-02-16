<template>
    <div class="banner">
            <div class="banner-animation">
                <img  src="@/assets/image/banner/THEF2E.png" class="banner-thef2e">
                <img src="@/assets/image/banner/4th.png" class="banner-4th">
                   
                <p class="banner-text">互動式網頁設計</p>
                <button class="banner-btn">
                    <p class="banner-btn-text">立即報名</p>
                </button>

                <img src="@/assets/image/banner/code.png" alt="" class="bannerimg banner-code"/>
                <img src="@/assets/image/banner/line2.png" alt="" class="bannerimg banner-line2"/>

                <img src="@/assets/image/banner/dashboard.png" alt="" class="bannerimg banner-dashboard" />
                <img src="@/assets/image/banner/line.png" alt="" class="bannerimg banner-line"/>
                
            </div>

            <div class="join-us">
                <img src="@/assets/image/banner/joinus.png" alt="" class="img-joinus"/>
                <img src="@/assets/image/banner/star.png" alt="" class="img-star">
            </div>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style lang="less" scoped>
    .banner {
        max-width: 1440px;
        margin: 0 auto;
        height: 720px;
    }
    .banner-animation {
       position: relative;
       height: 640px;
    }
    .banner-contant{
        position: relative; 
    }
    .banner-text {
        color: #fff;
        font-size: 28px;
        letter-spacing:20px;
        position: absolute;
        
        top: 255px;
        left:39%;
    }
    .banner-btn {
        width: 240px;
        text-align: center;
        align-items: center;
        padding: 23px 43px;
        border-radius: 50px;
        background-color: #ffe34e;
        position: absolute;
        top: 345px;
        left: 42%;
        border: 1px solid transparent;
        &-text { 
            color: #000;
            font-size: 22px;
            font-weight: 600;
            letter-spacing: 2px;
        }
    }
    .banner-4th {
        position: absolute;
        right: 25%;
        top: 13%;
    }
    .banner-thef2e {
        position: absolute;
        right: 34%;
        top: 20%;
    }
    .bannerimg {
        position: relative;
    }
    .banner-code {
        top: 15px;
        left: 95px;
        width: 165px;
    }
    .banner-line2 {
        top: 70px;
        left: 105px;
        width: 245px;
    }
    
    .banner-dashboard {
        top: 150px;
        left:500px;
        width: 304px;
    }

    .banner-line {
        left: 440px;
        bottom: 12px;
        width: 194px;
    }
    .join-us {
        position: relative;
        top:10px;
    }
    .img-star {
        position: relative;
        bottom: 18px;
        left: 20px;
    }

</style>