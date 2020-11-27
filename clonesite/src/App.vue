<template>
  <div id="app">
    <div id="nav">
      <headertitle></headertitle>
    </div>
    <router-view/>
    <div class="quich_menu">
        <ul class="shadow-sm">
            <li>
                <a href="">참가신청</a>
            </li>
            <li>
                <!--<a href="/marathon/volunteer/guide.do">후원하기</a>-->
                <a href="/support/supportMonth.do">후원하기</a>
            </li>
            <li>
                <a href="/marathon/info/faq.do">FAQ</a>
            </li>
        </ul>
        <a href="#" class="go_top"><span>TOP</span></a>
    </div>
  <Footer></Footer>
  </div>
</template>

<script>
import headertitle from './components/header';
import Footer from './components/footer';
export default {
  components:{
    headertitle,
    Footer
  },
}
</script>
<style>
.quich_menu {
  position: fixed;
    top: 35%;
    right: 30px;
    text-align: center;
    z-index: 500;
}
.shadow-sm {
  list-style: none;
    padding: 0;
    margin: 0;
    position: relative;
    border: 1px solid rgba(255,255,255,0.5);
    border-radius: 2px;
    box-shadow: 0 0.125rem 0.25rem rgba(0,0,0,0.075)
}
.quich_menu>ul:before {
    content: "";
    width: 70px;
    height: 80px;
    position: absolute;
    top: -74px;
    left: 0;
    right: 0;
    margin: auto;
    background-image: url('https://www.sc.or.kr/webPub/0_sck2014/images/marathon_2020/quick_header.png');
    background-repeat: no-repeat;
    background-size: 70px;
}
.quich_menu>ul>li:first-child>a {
    border-top-left-radius: 2px;
    border-top-right-radius: 2px;
}
.quich_menu>ul>li:nth-child(odd)>a {
    background-color: #ffeff0;
}
.quich_menu>ul>li>a {
    display: block;
    width: 82px;
    height: 82px;
    background-color: #e4f7f6;
    background-repeat: no-repeat;
    background-image: url('https://www.sc.or.kr/webPub/0_sck2014/images/marathon_2020/quick_add.png');
    background-position: 28px 14px;
    line-height: 125px;
    font-size: 13px;
    color: #414141;
    letter-spacing: -0.38px;
}

.quich_menu>ul>li:nth-child(2)>a {
    background-image: url('https://www.sc.or.kr/webPub/0_sck2014/images/marathon_2020/quick_donate.png');
    background-position: center 14px;
}
a:link, a:visited {
    text-decoration: none;
    color: #666;
    /* outline: none!important; */
}
.quich_menu>ul>li:nth-child(3)>a {
    background-image: url('https://www.sc.or.kr/webPub/0_sck2014/images/marathon_2020/quick_faq.png');
    background-position: center 14px;
}
.quich_menu .go_top {
    display: block;
    text-align: center;
    font-size: 12px;
    color: #414141;
    padding-top: 17px;
    position: relative;
}

.quich_menu .go_top:before {
    content: "";
    width: 0;
    height: 0;
    border: 4px solid transparent;
    border-bottom-color: #414141;
    position: absolute;
    top: 7px;
    margin: auto;
    left: 0;
    right: 0;
}
</style>
