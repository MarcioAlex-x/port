<template>
  <div class="total">
      <div class="content pb-5">
        <div class="container-fluid row pt-5">
          <div class="iframe d-flex flex-row-reverse col-lg-6 col-md-12 col-sm-12">
            <iframe
              class="bg-light"
              src="https://parahybaskajazz.netlify.app"
              frameborder="0"
              width="650"
              height="300"
            ></iframe>
          </div>
          <div class="content col-lg-6 col-md-12 col-sm-12">
            <h4>Parahyba Ska Jazz</h4>
            <p>
              Parahyba Ska Jazz é uma banda paraibana com destaque internacional.
              <br />
              Site feito totalmente com HTML5 e CSS3
            </p>
            <button class="btn  btn-outline-secondary">
              <a href="https://parahybaskajazz.netlify.app">Acesse</a>
            </button>
          </div>
        </div>
        <hr />
        <div class="container-fluid row pt-5">
          <div class="iframe d-flex flex-row-reverse col-lg-6 col-md-12 col-sm-12">
            <iframe
              class="bg-light"
              src="https://alexfreitas.netlify.app"
              frameborder="0"
              width="650"
              height="300"
            ></iframe>
          </div>
          <div class="content col-lg-6 col-dm-12 col-sm-12">
            <h4>Alex Freitas</h4>
            <p>
              Alex Freitas foi uma ideia de plataforma de reunião de conteúdo de
              estudos totalmente gratuito voltado para tecnologia
              <br />
              Site feito com Bootstrap
            </p>
            <button class="btn  btn-outline-secondary">
              <a href="https://parahybaskajazz.netlify.app">Acesse</a>
            </button>
          </div>
        </div>
        <hr>
         <div class="container-fluid row pt-5">
          <div class="iframe d-flex flex-row-reverse col-lg-6 col-md-12 col-sm-12">
            <iframe
              class="bg-light"
              src="https://cadastropreaprovado.netlify.app"
              frameborder="0"
              width="650"
              height="300"
            ></iframe>
          </div>
          <div class="content col-lg-6 col-md-12 col-sm-12">
            <h4>Cadastro pré aprovado</h4>
            <p>
              Página criada para auxiliar a minha esposa na aquisição de novos cadastros para o seu grupo.
              <br />
              Site feito com Bootstrap
            </p>
            <button class="btn  btn-outline-secondary">
              <a href="https://cadastropreaprovado.netlify.app">Acesse</a>
            </button>
          </div>
        </div>
        <hr>
        <div class="container-fluid row pt-5">
          <div class="iframe d-flex flex-row-reverse col-lg-6 col-md-12 col-sm-12">
            <iframe
              class="bg-light"
              src="https://alfatecjp.netlify.app"
              frameborder="0"
              width="650"
              height="300"
            ></iframe>
          </div>
          <div class="content col-lg-6 col-md-12 col-sm-12">
            <h4>Alfatec Celulares</h4>
            <p>
      
              Uma assistência técnica especializada em notebook e mobiles
              <br />
              Criado com HTML e CSS.
            </p>
            <button class="btn  btn-outline-secondary">
              <a href="">Acesse</a>
            </button>
          </div>
        </div>
      
  </div>
    
  </div>
</template>

<script>
export default {
  nome: "ContentBanner",
};
</script>

<style scoped>

.total{
    background: rgba(92, 89, 89, 0.493);
}
iframe{
    border: 10px solid rgb(71, 65, 65);
    border-style: double;
}
.content {
  color: #F0CF99;
  font-size: 1.2em;
  align-self: center;
  
}
h4 {
  font-size: 1.5em;
}
a {
  color: white;
  text-decoration: none;
}
a:hover {
  color: beige;
}
@media screen and (max-width: 988px) {
    .content{
        text-align: justify;
        margin: 15px;
    }
    .iframe{
        flex-direction: unset;
        justify-content: center;
    }
}
@media screen and (max-width: 600px) {
    .iframe{
        width: 400;
        height: 150;
    }
}






</style>