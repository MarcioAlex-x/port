<template>
  <div class="container-fluid row mt-2 pt-5 p-5">
    <div class="tecnologies col-lg-6">
      <div class="icones row d-flex justify-content-around">
        <img src="../assets/img/html.png" class="col-2 p-2" alt="" />
        <img src="../assets/img/css-3.png" class="col-2 p-2" alt="" />
        <img src="../assets/img/sass.png" class="col-2 p-2" alt="" />
      </div>
      <div class="icones row d-flex justify-content-around">
        <img src="../assets/img/git.png" class="col-2 p-2" alt="" />
        <img src="../assets/img/script-java.png" class="col-2 p-2" alt="" />
        <img src="../assets/img/python.png" class="col-2 p-2" alt="" />
      </div>
    </div>
    <div class="content col-lg-6 col-sm-12 col-md-12">
      Cursando o primeiro período de sistemas para internet na Uniesp,
      Cabedelo-PB, eu já tenho domínio em HTML5, CSS3, Sass, Bootstrap,
      Javascript, Python e Vue. Na faculdade estou estudando dados com Python e
      programação com Java.
    </div>
  </div>
</template>

<script>
export default {
  name: "SecondBanner",
};
</script>

<style scoped>
.container-fluid {
  background: white;
  margin: 0;
  box-sizing: border-box;
}
.content {
  font-size: 1.3em;
  padding: 10px;
  text-align: justify;
  align-self: center;
}
@media screen and (max-width: 768px) {
    img {
        display: none;
  }
    .content {
        font-size: 1em;
  }
}
</style>