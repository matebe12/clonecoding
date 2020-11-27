<template>
<div>
    <Slider></Slider>
    <div class="imgVideo">
        <iframe width="727" height="409" src="https://www.youtube.com/embed/3nnfdErsadk" 
        frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
         allowfullscreen>
         </iframe>
    </div>
    <div class="main-photo">
		<div class="container">
			<ul class="photoButton">
				<li class="total">
					<a class="nav-link active" href="#" data-toggle="pill" >전체사진</a>
				</li>
				<li class="item">
					<a class="nav-link" href="#" data-toggle="pill">중부권</a>
				</li>
				<li class="item">
					<a class="nav-link" href="#" data-toggle="pill" >남부권</a>
				</li>
				<li class="item">
					<a class="nav-link" href="#" data-toggle="pill" >동부권</a>
				</li>
				<li class="item">
					<a class="nav-link" href="#" data-toggle="pill" >호남권</a>
				</li>
				<li class="item">
					<a class="nav-link" href="#" data-toggle="pill" >충청권</a>
				</li>
			</ul>

			<div class="photo-grid row-grid" id="photo_grid"><div class="col-xl-4 col-lg-4 col-6"><a href="#" onclick="clickEvent(`메인 이미지 클릭`)" class="photo" data-toggle="modal" data-target="#imageModal" data-img="/marathon/editImgUp.do?filePath=/sc_home/upload/marathon/oBQhxNesGUahTso1PcgPrtaaOg5MJ1ph6voQ4sSFTkA3kx9MV81yz1uMEujfv7I5.amV1c19kb21haW4vc2VydmVyMl9iYWs=_35d8532c-84a5-4c26-ae05-364b61f56eab.jpg" style="background-image: url(/marathon/editImgUp.do?filePath=/sc_home/upload/marathon/oBQhxNesGUahTso1PcgPrtaaOg5MJ1ph6voQ4sSFTkA3kx9MV81yz1uMEujfv7I5.amV1c19kb21haW4vc2VydmVyMl9iYWs=_35d8532c-84a5-4c26-ae05-364b61f56eab.jpg);"></a></div><div class="col-xl-4 col-lg-4 col-6"><a href="#" onclick="clickEvent(`메인 이미지 클릭`)" class="photo" data-toggle="modal" data-target="#imageModal" data-img="/marathon/editImgUp.do?filePath=/sc_home/upload/marathon/zbo1Zq5vpusjOaEzmqBPdgs1cyKk3hd76OuP8p1lebi2nSClVJ1WN7m1nl9jG6xu.amV1c19kb21haW4vc2VydmVyMQ==_81ce28b0-a935-4422-a716-c05411218221.png" style="background-image: url(/marathon/editImgUp.do?filePath=/sc_home/upload/marathon/zbo1Zq5vpusjOaEzmqBPdgs1cyKk3hd76OuP8p1lebi2nSClVJ1WN7m1nl9jG6xu.amV1c19kb21haW4vc2VydmVyMQ==_81ce28b0-a935-4422-a716-c05411218221.png);"></a></div><div class="col-xl-4 col-lg-4 col-6"><a href="#" onclick="clickEvent(`메인 이미지 클릭`)" class="photo" data-toggle="modal" data-target="#imageModal" data-img="/marathon/editImgUp.do?filePath=/sc_home/upload/marathon/gt0hVe4kEF9M1s9jfrgA6yxZ7fDZlH0M6edEdKkVl4RohfSEV6n1OevBLAGfAGxX.amV1c19kb21haW4vc2VydmVyMl9iYWs=_5d3a3d76-49dc-4ddc-99d4-938848c64bef.jpg" style="background-image: url(/marathon/editImgUp.do?filePath=/sc_home/upload/marathon/gt0hVe4kEF9M1s9jfrgA6yxZ7fDZlH0M6edEdKkVl4RohfSEV6n1OevBLAGfAGxX.amV1c19kb21haW4vc2VydmVyMl9iYWs=_5d3a3d76-49dc-4ddc-99d4-938848c64bef.jpg);"></a></div><div class="col-xl-4 col-lg-4 col-6"><a href="#" onclick="clickEvent(`메인 이미지 클릭`)" class="photo" data-toggle="modal" data-target="#imageModal" data-img="/marathon/editImgUp.do?filePath=/sc_home/upload/marathon/TYDXvRPTIjoYNawe5RHL0UWPZi1fegra66ga80mDeyuliMg6VdHj7Fong3T2K5AY.amV1c19kb21haW4vc2VydmVyMQ==_dec1b113-5ba4-468b-8782-85142b226159.jpg" style="background-image: url(/marathon/editImgUp.do?filePath=/sc_home/upload/marathon/TYDXvRPTIjoYNawe5RHL0UWPZi1fegra66ga80mDeyuliMg6VdHj7Fong3T2K5AY.amV1c19kb21haW4vc2VydmVyMQ==_dec1b113-5ba4-468b-8782-85142b226159.jpg);"></a></div><div class="col-xl-4 col-lg-4 col-6"><a href="#" onclick="clickEvent(`메인 이미지 클릭`)" class="photo" data-toggle="modal" data-target="#imageModal" data-img="/marathon/editImgUp.do?filePath=/sc_home/upload/marathon/QIa1v6xglvA6YBfVaHv1hiLWuqRs1RgW6q0P2qzTgQTaxi0PVJAyzuauIvka9VLa.amV1c19kb21haW4vc2VydmVyMl9iYWs=_918171f0-fda8-408e-a067-1ab0d7cdd4c5.jpg" style="background-image: url(/marathon/editImgUp.do?filePath=/sc_home/upload/marathon/QIa1v6xglvA6YBfVaHv1hiLWuqRs1RgW6q0P2qzTgQTaxi0PVJAyzuauIvka9VLa.amV1c19kb21haW4vc2VydmVyMl9iYWs=_918171f0-fda8-408e-a067-1ab0d7cdd4c5.jpg);"></a></div><div class="col-xl-4 col-lg-4 col-6"><a href="#" onclick="clickEvent(`메인 이미지 클릭`)" class="photo" data-toggle="modal" data-target="#imageModal" data-img="/marathon/editImgUp.do?filePath=/sc_home/upload/marathon/ZX6NMQyazQyQpfzSnBc86KZ4g6F229ph6mwRo2XNLjSbbHLMVr5K3ZQ2iSGojy3N.amV1c19kb21haW4vc2VydmVyMQ==_6ee47a36-8d77-46db-b772-3524af1ebfc7.jpg" style="background-image: url(/marathon/editImgUp.do?filePath=/sc_home/upload/marathon/ZX6NMQyazQyQpfzSnBc86KZ4g6F229ph6mwRo2XNLjSbbHLMVr5K3ZQ2iSGojy3N.amV1c19kb21haW4vc2VydmVyMQ==_6ee47a36-8d77-46db-b772-3524af1ebfc7.jpg);"></a></div><div class="col-xl-4 col-lg-4 col-6"><a href="#" onclick="clickEvent(`메인 이미지 클릭`)" class="photo" data-toggle="modal" data-target="#imageModal" data-img="/marathon/editImgUp.do?filePath=/sc_home/upload/marathon/Hgdxf9dhV1bRgAJSjnw0GWQPKGLRlK0a63PJTSpDQQhOabIrVbnqtuhDhAM94jta.amV1c19kb21haW4vc2VydmVyMQ==_671e8ea2-56e0-4c8a-9b44-6d6c9413b172.jpg" style="background-image: url(/marathon/editImgUp.do?filePath=/sc_home/upload/marathon/Hgdxf9dhV1bRgAJSjnw0GWQPKGLRlK0a63PJTSpDQQhOabIrVbnqtuhDhAM94jta.amV1c19kb21haW4vc2VydmVyMQ==_671e8ea2-56e0-4c8a-9b44-6d6c9413b172.jpg);"></a></div><div class="col-xl-4 col-lg-4 col-6"><a href="#" onclick="clickEvent(`메인 이미지 클릭`)" class="photo" data-toggle="modal" data-target="#imageModal" data-img="/marathon/editImgUp.do?filePath=/sc_home/upload/marathon/ix799sBtdIyfL11aztpJf4se64FM7dGC63OakgI1EBbasSUMVj7K2sAjdBxAv1TY.amV1c19kb21haW4vc2VydmVyMQ==_b49efa43-01bb-4590-a59c-b1a5beb87dd5.jpg" style="background-image: url(/marathon/editImgUp.do?filePath=/sc_home/upload/marathon/ix799sBtdIyfL11aztpJf4se64FM7dGC63OakgI1EBbasSUMVj7K2sAjdBxAv1TY.amV1c19kb21haW4vc2VydmVyMQ==_b49efa43-01bb-4590-a59c-b1a5beb87dd5.jpg);"></a></div><div class="col-xl-4 col-lg-4 col-6"><a href="#" onclick="clickEvent(`메인 이미지 클릭`)" class="photo" data-toggle="modal" data-target="#imageModal" data-img="/marathon/editImgUp.do?filePath=/sc_home/upload/marathon/qxh8aETZDzosxzlFxbQ0HdJWTqCN6v016tXsI1z0bS90x7WmVSefoTCbIOEu3Fhh.amV1c19kb21haW4vc2VydmVyMQ==_da9a72ca-45a3-48f8-82d4-f96721beb1e0.jpg" style="background-image: url(/marathon/editImgUp.do?filePath=/sc_home/upload/marathon/qxh8aETZDzosxzlFxbQ0HdJWTqCN6v016tXsI1z0bS90x7WmVSefoTCbIOEu3Fhh.amV1c19kb21haW4vc2VydmVyMQ==_da9a72ca-45a3-48f8-82d4-f96721beb1e0.jpg);"></a></div><div class="col-xl-4 col-lg-4 col-6"><a href="#" onclick="clickEvent(`메인 이미지 클릭`)" class="photo" data-toggle="modal" data-target="#imageModal" data-img="/marathon/editImgUp.do?filePath=/sc_home/upload/marathon/Ss6s5mRDmv6F05LLQkzFSK12DnPjKF616N8RF3Q7zLyeE1erVXyBIJ1qvInJeHz9.amV1c19kb21haW4vc2VydmVyMl9iYWs=_f6482574-28b2-4382-850a-6e9dec06340e.jpg" style="background-image: url(/marathon/editImgUp.do?filePath=/sc_home/upload/marathon/Ss6s5mRDmv6F05LLQkzFSK12DnPjKF616N8RF3Q7zLyeE1erVXyBIJ1qvInJeHz9.amV1c19kb21haW4vc2VydmVyMl9iYWs=_f6482574-28b2-4382-850a-6e9dec06340e.jpg);"></a></div><div class="col-xl-4 col-lg-4 col-6"><a href="#" onclick="clickEvent(`메인 이미지 클릭`)" class="photo" data-toggle="modal" data-target="#imageModal" data-img="/marathon/editImgUp.do?filePath=/sc_home/upload/marathon/kOudSIEXwu1yrHlV7W7gx5452V9k0NQI6QezWHIVKR191kRIVCQIOGRJabJvPRZH.amV1c19kb21haW4vc2VydmVyMQ==_7d4c9077-3eb2-492f-9783-3d597f083c59.jpg" style="background-image: url(/marathon/editImgUp.do?filePath=/sc_home/upload/marathon/kOudSIEXwu1yrHlV7W7gx5452V9k0NQI6QezWHIVKR191kRIVCQIOGRJabJvPRZH.amV1c19kb21haW4vc2VydmVyMQ==_7d4c9077-3eb2-492f-9783-3d597f083c59.jpg);"></a></div><div class="col-xl-4 col-lg-4 col-6"><a href="#" onclick="clickEvent(`메인 이미지 클릭`)" class="photo" data-toggle="modal" data-target="#imageModal" data-img="/marathon/editImgUp.do?filePath=/sc_home/upload/marathon/dfWkhgEgOr3YVh9M70t1Smkc7k3Yxj1q6X9ZjOzkaSGiuebMV7qA0J5szw5tZNZi.amV1c19kb21haW4vc2VydmVyMl9iYWs=_0f42f2e1-e82e-4868-8045-2a72ac6de27b.jpg" style="background-image: url(/marathon/editImgUp.do?filePath=/sc_home/upload/marathon/dfWkhgEgOr3YVh9M70t1Smkc7k3Yxj1q6X9ZjOzkaSGiuebMV7qA0J5szw5tZNZi.amV1c19kb21haW4vc2VydmVyMl9iYWs=_0f42f2e1-e82e-4868-8045-2a72ac6de27b.jpg);"></a></div></div>

		</div>
        <div class="photozone">
            <div> <img src="https://www.sc.or.kr/marathon/editImgUp.do?filePath=/sc_home/upload/marathon/oBQhxNesGUahTso1PcgPrtaaOg5MJ1ph6voQ4sSFTkA3kx9MV81yz1uMEujfv7I5.amV1c19kb21haW4vc2VydmVyMl9iYWs=_35d8532c-84a5-4c26-ae05-364b61f56eab.jpg" alt="">
            </div>
            <div> <img src="https://www.sc.or.kr/marathon/editImgUp.do?filePath=/sc_home/upload/marathon/zbo1Zq5vpusjOaEzmqBPdgs1cyKk3hd76OuP8p1lebi2nSClVJ1WN7m1nl9jG6xu.amV1c19kb21haW4vc2VydmVyMQ==_81ce28b0-a935-4422-a716-c05411218221.png" alt="">
            </div>
            <div> <img src="https://www.sc.or.kr/marathon/editImgUp.do?filePath=/sc_home/upload/marathon/gt0hVe4kEF9M1s9jfrgA6yxZ7fDZlH0M6edEdKkVl4RohfSEV6n1OevBLAGfAGxX.amV1c19kb21haW4vc2VydmVyMl9iYWs=_5d3a3d76-49dc-4ddc-99d4-938848c64bef.jpg" alt="">
            </div>
            <div> <img src="https://www.sc.or.kr/marathon/editImgUp.do?filePath=/sc_home/upload/marathon/TYDXvRPTIjoYNawe5RHL0UWPZi1fegra66ga80mDeyuliMg6VdHj7Fong3T2K5AY.amV1c19kb21haW4vc2VydmVyMQ==_dec1b113-5ba4-468b-8782-85142b226159.jpg" alt="">
            </div>
            <div> <img src="https://www.sc.or.kr/marathon/editImgUp.do?filePath=/sc_home/upload/marathon/QIa1v6xglvA6YBfVaHv1hiLWuqRs1RgW6q0P2qzTgQTaxi0PVJAyzuauIvka9VLa.amV1c19kb21haW4vc2VydmVyMl9iYWs=_918171f0-fda8-408e-a067-1ab0d7cdd4c5.jpg" alt="">
            </div>
            <div> <img src="https://www.sc.or.kr/marathon/editImgUp.do?filePath=/sc_home/upload/marathon/ZX6NMQyazQyQpfzSnBc86KZ4g6F229ph6mwRo2XNLjSbbHLMVr5K3ZQ2iSGojy3N.amV1c19kb21haW4vc2VydmVyMQ==_6ee47a36-8d77-46db-b772-3524af1ebfc7.jpg" alt="">
            </div>
            <div> <img src="https://www.sc.or.kr/marathon/editImgUp.do?filePath=/sc_home/upload/marathon/Hgdxf9dhV1bRgAJSjnw0GWQPKGLRlK0a63PJTSpDQQhOabIrVbnqtuhDhAM94jta.amV1c19kb21haW4vc2VydmVyMQ==_671e8ea2-56e0-4c8a-9b44-6d6c9413b172.jpg" alt="">
            </div>
            <div> <img src="https://www.sc.or.kr/marathon/editImgUp.do?filePath=/sc_home/upload/marathon/ix799sBtdIyfL11aztpJf4se64FM7dGC63OakgI1EBbasSUMVj7K2sAjdBxAv1TY.amV1c19kb21haW4vc2VydmVyMQ==_b49efa43-01bb-4590-a59c-b1a5beb87dd5.jpg" alt="">
            </div>
            <div> <img src="https://www.sc.or.kr/marathon/editImgUp.do?filePath=/sc_home/upload/marathon/qxh8aETZDzosxzlFxbQ0HdJWTqCN6v016tXsI1z0bS90x7WmVSefoTCbIOEu3Fhh.amV1c19kb21haW4vc2VydmVyMQ==_da9a72ca-45a3-48f8-82d4-f96721beb1e0.jpg" alt="">
            </div>
        </div>
        <div class="btncenter">
            <div id="btnMore">
				<button type="button" @click="showAlert()">더보기</button>
			</div>
        </div>
            
	</div>
</div>

</template>

<script>
import Slider from '../components/slider';
//import axios from 'axios';
export default {
    components:{
        Slider
    },
    data() {
        return {
            page: 1,
            area: '',
        }
    },
    methods: {
        showAlert(){
            alert('CORS문제때문에 api 호출 불가!')
        }
    },
}
</script>

<style scoped>
.imgVideo {
    width: 100%;
    height: 660px;
    background-image: url('https://www.sc.or.kr/webPub/0_sck2014/images/marathon_2020/main_movie_cover.png');
    background-repeat: no-repeat;
    background-position: center bottom;
    display: flex;
    justify-content: center;
    align-items: center;
    }
.photoButton {
    display: flex;
    list-style: none;
    margin-top: 10%;
    justify-content: center;
}
.photozone {
    display: grid;
    grid-template-columns: repeat(3, 380px);
  grid-gap: 10px;
  grid-auto-rows: minmax(100px, auto);
  justify-content: center;
}
.photozone img {
    height: 360px;
}
.btncenter {
    display: flex;
    justify-content: center;
    margin-top: 100px;
}
#btnMore button{
    width: 360px;
    height: 60px;
    line-height: 60px;
    padding: 0;
    font-size: 20px;
    letter-spacing: -0.38px;
    background-color: #ed1b23;
    border-color: #ed1b23;
    border-radius: 50rem;
    color: white;
    border: none;
    cursor: pointer;
}
#btnMore button:focus {
    outline: none;
}
.photoButton li {
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: #23cec2;
    width:100px;
  height:100px;
  border-radius: 50px;
  margin-right: 30px;
    transition:all 150ms linear;
}

.photoButton li a {
    font-size: 18px;
    font-weight: 700;
    color: aliceblue;
}

.photoButton .total {
    background-color: #ed1b23;
}
.photoButton .item a, .photoButton .total a{
    text-decoration: none;
}
.photoButton li:hover {
    width:130px;
    height: 130px;
    border-radius: 65px;
    transition:all 150ms linear;
}
</style>