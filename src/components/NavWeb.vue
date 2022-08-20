<template>
  <div class="container-fluid position-relative">
    <div class="row">
        <div class="col-lg-6 col-md-4">
            <img src="../assets/img/Marcio.png" alt="">
        </div>

        <div class="lista col-lg-6 col-md-8 col-sm-10">
            <ul class=" d-flex flex-row-reverse  ">
                <li><a href="https://github.com/MarcioAlex-x" target="_blank">Github</a></li>
                <li><a href="https://www.linkedin.com/in/alex-freitas-6a510621a/" target="_blank">Linkedin</a></li>
            </ul>
        </div>
    </div>
  </div>
</template>

<script>
export default {
    name: 'NavWeb'
}
</script>

<style scoped>
    
    ul{
        display: flex;
    }
    li{
        list-style: none;
    }
    
    a{
        cursor: pointer;
        color: #F0CF99;
        padding: 10px 40px;
        text-align: right;
        font-size: 1.5em;
        text-decoration: none;
        margin: 5px;
    }
    a:hover{
        color: #5f3c04;
        background: #F0CF99;
        border-radius: 5px;
    }
    p{
        color: white;
        font-size: 1.3em;
    }

    @media screen and (max-width:765px) {
        .lista {
            display: none;
        }
    }
   
    
</style>