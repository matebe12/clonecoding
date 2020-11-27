<template>
  <footer>
    <div class="footer" id="contact">
      <ul>
        <li class="li-f">
          <a href="https://github.com/matebe12/">
            <img :src="require('../assets/git.png')" class="git-image" />
          </a>
        </li>
        <li><span>이 사이트는 개발 포트폴리오용 사이트 입니다.</span></li>
        <li class="email"><span>matebe12@gmail.com</span></li>
      </ul>
    </div>
  </footer>
</template>

<script>
export default {};
</script>

<style>
footer {
  width: 100%;
  margin-top: 300px;
}
.footer {
  display: flex;
  background: gray;
  padding: 0.5%;
  justify-content: center;
  justify-items: unset;
}
.git-image {
  width: 30px;
  height: 30px;
}
ul {
  list-style: none;
}
ul .li-f {
  text-align: center;
}
.email {
  text-align: center;
}
</style>
