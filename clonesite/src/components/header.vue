
<template>
<header>
<div class="main-menu">
    <div class="container">
        <nav class="header">
            <div class="logo">
                <img src="https://www.sc.or.kr/webPub/0_sck2014/images/marathon_2020/logo.png" alt="">        
            </div>
            <ul class="menu">
                
                <li class="main">
                    <router-link to="" class="parent">국제 어린이 마라톤</router-link>
                    <div class="submenu">
                        <li>
                            <router-link to="">마라톤의 의미</router-link>
                            <router-link to="">우리가 만드는 변화</router-link>
                        </li>
                    </div>
                </li>
                <li class="main">
                    <router-link to="" class="parent">마라톤 행사 안내</router-link>
                    <div class="submenu">
                        <li>
                            <router-link to="">2020 런택트 마라톤</router-link>
                        </li>
                    </div>
                </li>
                <li class="main">
                    <router-link to="" class="parent">참가 신청</router-link>
                    <div class="submenu">
                        <li>
                            <router-link to="">참가 신청 안내</router-link>
                            <router-link to="">참가 신청</router-link>
                            <router-link to="">참가 신청 확인</router-link>
                        </li>
                    </div>
                </li>
                <li class="main">
                    <router-link to="" class="parent">커뮤니티</router-link>
                    <div class="submenu">
                        <li>
                            <router-link to="">공지 사항</router-link>
                            <router-link to="">FAQ</router-link>
                        </li>
                    </div>
                </li>
            </ul>
        </nav>
    </div>
</div>
</header>

   
</template>

<script>
export default {
}
</script>

<style scoped>
    .main-menu {
        position: relative;
    }
    header .header .menu {
        list-style: none;
    margin: 0;
    padding: 0;
    display: inline-flex;
    }
    .header {
        display: flex;
        justify-content: space-evenly;
    }
    ul{
        list-style: none;
        line-height: 78px;
    }
    .menu {
        
        background: white;
    }
    .submenu {
        margin-top: 5px;
        display: none;
        opacity: 1;
        transition:all 50ms ease;
    }
    a {
        text-decoration: none;
        color: black;
            display: block;
    font-size: 19px;
    letter-spacing: -0.38px;
    padding: 0 20px;
    margin-left: 10px;
    margin-right: 10px;
    position: relative;
    padding-bottom: 30px;
    padding-bottom: 0;
    }
    .menu > li > a {
        border-bottom: 1px solid #eee;
        text-align: left;
    }
    .submenu li a {
        font-size: 15px;
        text-align: center;
    }
    .submenu li a:hover {
        background-color: blanchedalmond;
        transition:all 150ms linear;
    }
    ul:hover .submenu{
        display: block;
        transition:all 50ms ease;
        z-index: 9998;
    }
    .main:hover  .parent{
        border-bottom: 2px solid red;
        transition:all 100ms linear;
    }
    a:visited{
        color: black;
    }
    .container {
        width: 100%;
        padding-right: 10px;
        padding-left: 10px;
        margin-right: auto;
        margin-left: auto;
    }
    .header {
        margin-top: 40px;
    }
    
</style>