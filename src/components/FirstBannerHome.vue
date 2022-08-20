<template>
  <div class="container">
    <div class="row">
        <div class="img-banner col-lg-6 sm-12 lg-12">
            <img  class="p-3" src="../assets/img/MarcioAlex.png" alt="">
        </div>
        <div class="banner col-lg-6 md-12 sm-12 headerBanner">
        
            <h3 class="pt-5 mt-5">Que bom ter você por aqui</h3> 
            <div class="headerBanner mt-5">
                <h1 class="pt-4">Márcio Freitas</h1>
                <h2>Estudante de Sistemas para Internet</h2>
            </div>
              
        </div>
        
    </div>
  </div>

</template>

<script>
export default {
  name: "FirstBannerHome",
  data() {
    return {};
  },
};
</script>

<style scoped>
    
    .container{
        color: #F0CF99;
        background: url("../assets/img/bgDark.png");
        background-size: cover;
    }
    h3{
        font-size: 9em;
        letter-spacing: -5px;
        word-spacing: 1px;
        line-height: 0.8 ;
        font-family: 'Ruda';
        font-weight: 900;
    }
    h1, h2{
        font-family: 'Ruda';
        font-weight: bolder;
    }
     img{
        animation: imagem 1s ease-in-out;
    }
    @keyframes imagem {
        0%{
            transform: translate(-150px);
            opacity: 0;
        }
        100%{
            transform: translateX(0)
            
        }
    }
    .banner{
        animation: banner 1s ease-in-out;
    }
     @keyframes banner {
        0%{
            transform: translate(150px);
            opacity: 0;
        }
        100%{
            transform: translateX(0)
            
        }
   
     }
     @media screen and (max-width: 1084px) {
        h3{
            font-size: 4.2em;
        }
     }

    @media screen and (max-width: 912px) {
        .img-banner{
            display: none;
        }
        h3{
            font-size: 5em;
        }
    }
    
    

</style>