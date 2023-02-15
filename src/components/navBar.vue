<template>
    <div class="header">
        <div class="logo">
          <a href="/">
            <img src="@/assets/logo.png" alt="f2elogo" />
          </a>
        </div>
        <nav class="navbar">
          <ul class="navbar-nav nav-normal">
            <li class="nav-item">
              <a class="nav-link text-link" href="">關卡資訊</a>
            </li>
            <li class="nav-item">
              <a class="nav-link text-link" href="">活動說明</a>
            </li>
            <li class="nav-item">
              <a class="nav-link text-link" href="">攻略資源</a>
            </li>
            <li class="nav-item">
              <a class="nav-link text-link" href="">求職專區</a>
            </li>
            <li class="nav-item ">
              <a class="nav-link  button-small login-btn" href="/">登入</a>
            </li>
          </ul>
        </nav>
      </div>
</template>

<script>
    export default {
        
    }
</script>

<style lang="less" scoped>

.header { 
    display: flex;
    justify-content: space-between;
    flex-direction: row;
    padding-right: 2rem;
    padding-left: 2rem;
    height: 90px;
    .logo {
        display: flex;
        align-items: center;
        a {
          height: 22px;
        }
        img {
          width: 182px;
          height: inherit;
        }
    }

    .navbar {
        display: flex;
        text-align: right;
        .navbar-nav {
            list-style-type: none;
            display: flex;
            align-items: center;
            .nav-item {
                font-family: 'Noto Sans CJK TC';
                font-style: normal;
                display: flex;
            }
            .nav-link {
                text-decoration: none;
            }
        }
        .nav-normal {
          gap:28px;
          margin: 0 30px;
        } 
        .button-small{
          border: 1px solid #fff;
          color: #fff;
          width: 80px;
          height: 40px;
          line-height: 40px;
          border-radius: 60px;
          align-items: center;
          text-align: center;
          margin-left: 10px;
        }
        .text-link {
          color: #858993;
        
        }
        .text-link:hover {
          color: #fff;
          position: relative;
          &::after{
            content: '';
            position: absolute;
            top:24px;
            right: 40%;
          width: 18%;
          height: 3px;
          background: #47fff6;
          border-radius: 50px;
          }
        }
        .login-btn {
          color: #fff;
        }
        .button-small:hover {
          color: #fff;
          position: relative;
          border: 1px solid #47fff6;
          &::after{
            content: '';
            position: absolute;
            top:0px;
            right:0%;
            width:100%;
            height: 100%;
            background: rgba(59, 213, 205, 0.5);
            border-radius: 50px;
          }
        }
    }
}


</style>