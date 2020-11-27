<template>
   <div class="slide-box">
        <div>
            <img src="https://www.sc.or.kr/webPub/0_sck2014/images/marathon_2020/main_swipe_1.jpg" alt="" class="img active fade">
            <img src="https://www.sc.or.kr/webPub/0_sck2014/images/marathon_2020/main_swipe_2.jpg" alt="" class="img fade">
            <img src="https://www.sc.or.kr/webPub/0_sck2014/images/marathon_2020/main_swipe_3.jpg" alt="" class="img fade">
            <button  class="left btn" id="left">{{left}}</button>
            <button  class="right btn" id="right">></button>
        </div>
        
    </div>
</template>

<script>
export default {
    data() {
        return {
            left: '<'
        }
    },
    mounted() {
         let cnt = 0;
        let timer = null;
        const left = document.getElementById('left');
        const right = document.getElementById('right');
        left.addEventListener('click', function() {
            clearInterval(timer);
            prev();
            interval();
        });
        right.addEventListener('click', function() {
            clearInterval(timer);
            next();
            interval();
        });

        function prev() {
            
                let img = document.getElementsByClassName('img');
                if(cnt <= 0) cnt = img.length -1;
                else cnt--;
                removeClassName();
                addClassName();
        }
        function next() {
                let img = document.getElementsByClassName('img');
                if(cnt >= img.length-1) cnt = 0;
                else cnt++;
                removeClassName();
                addClassName();
        }
        function removeClassName(){
            let img = document.getElementsByClassName('img');
            for(let i = 0; i < img.length; i++)
            img[i].classList.remove('active');
        }
        function addClassName(){
            let img = document.getElementsByClassName('img');
            img[cnt].classList.add('active');
        }
        function interval() {
            timer = setInterval(function(){
                next();
            },2000);
        }
        timer = setInterval(function(){
                next();
        },2000);
    },
}
</script>

<style scoped>
.slide-box {
            display: flex;
            justify-content: center;
            align-items: center;
            width: 100%;
            position: relative;
            z-index: -1;
        }
        .slide-box div {
            position: relative;
        }
        .img {
            display: none;
        }
        .active{
            display: block;
        }
        img {
            width: 100%;
            height: 600px;
        }
        button{
            opacity: 0.5;
            cursor: pointer;
        }
        .slide-box .left{
            position: absolute;
            top: 50%;
            left: 0;
        }
        .slide-box .right{
            position: absolute;
            top: 50%;
            right: 0;
        }
        .fade {
            -webkit-animation-name: fade;
            -webkit-animation-duration: 1.5s;
            animation-name: fade;
            animation-duration: 1.5s;
        }

        @-webkit-keyframes fade {
        from {opacity: .4} 
        to {opacity: 1}
        }

        @keyframes fade {
        from {opacity: .4} 
        to {opacity: 1}
        }

</style>