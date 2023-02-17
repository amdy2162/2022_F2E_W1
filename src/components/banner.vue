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

            <section class="section4">
                <ul class="loop">
                    <li>
                        <img src="@/assets/image/banner/joinus.png" alt="" class="img-joinus"/>
                        <img src="@/assets/image/banner/star.png" alt="" class="img-star"/>
                    </li>
                    <li>
                        <img src="@/assets/image/banner/joinus.png" alt="" class="img-joinus"/>
                        <img src="@/assets/image/banner/star.png" alt="" class="img-star"/>
                    </li>
                    <li>
                        <img src="@/assets/image/banner/joinus.png" alt="" class="img-joinus"/>
                        <img src="@/assets/image/banner/star.png" alt="" class="img-star"/>
                    </li>
                    <li>
                        <img src="@/assets/image/banner/joinus.png" alt="" class="img-joinus"/>
                        <img src="@/assets/image/banner/star.png" alt="" class="img-star"/>
                    </li>
                    <li>
                        <img src="@/assets/image/banner/joinus.png" alt="" class="img-joinus"/>
                        <img src="@/assets/image/banner/star.png" alt="" class="img-star"/>
                    </li>
                    <li>
                        <img src="@/assets/image/banner/joinus.png" alt="" class="img-joinus"/>
                        <img src="@/assets/image/banner/star.png" alt="" class="img-star"/>
                    </li>
                    <li>
                        <img src="@/assets/image/banner/joinus.png" alt="" class="img-joinus"/>
                        <img src="@/assets/image/banner/star.png" alt="" class="img-star"/>
                    </li>
                    <li>
                        <img src="@/assets/image/banner/joinus.png" alt="" class="img-joinus"/>
                        <img src="@/assets/image/banner/star.png" alt="" class="img-star"/>
                    </li>
                    <li>
                        <img src="@/assets/image/banner/joinus.png" alt="" class="img-joinus"/>
                        <img src="@/assets/image/banner/star.png" alt="" class="img-star"/>
                    </li>
                    <li>
                        <img src="@/assets/image/banner/joinus.png" alt="" class="img-joinus"/>
                        <img src="@/assets/image/banner/star.png" alt="" class="img-star"/>
                    </li>
                    <li>
                        <img src="@/assets/image/banner/joinus.png" alt="" class="img-joinus"/>
                        <img src="@/assets/image/banner/star.png" alt="" class="img-star"/>
                    </li>
                </ul>
            </section>
    </div>
</template>

<script>  
    import gsap from 'gsap'
    export default {
        mounted() {
            gsap.to('.loop', {
            xPercent: "-50",
            ease: "none",
            duration: 10,
            repeat: -1,
            });
            gsap.to('.banner-code', {y: 20, duration:1 })
            gsap.to('.banner-dashboard', {x: -20, duration:1,})
            
        }
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

    .section4 {
        overflow: hidden; /*隱藏超出外層容器的元素*/
        max-width: 100%;
      }
    
      .loop {
        display: inline-block;
        font-family: "Dela Gothic One";
        font-size: 5rem;
        color: transparent;
        white-space: nowrap; /*文字必須設為nowrap，否則文字會自動換行*/
        height: 100%;
        -webkit-text-stroke: 1px black;
      }
      .loop > li {
        display: inline-block;
      }
</style>