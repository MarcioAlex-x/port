<template>
  <div class="footer container-fluid">
    <div class="row">
    <div class="col-12">
            <ul class=" d-flex justify-content-evenly pt-3">
                <li><a href="https://github.com/MarcioAlex-x" target="_blank">Github</a></li>
                <li><a href="https://www.linkedin.com/in/alex-freitas-6a510621a/" target="_blank">Linkedin</a></li>
            </ul>
        </div>
        <div class="col-12">
            <p>Este portifólio foi desenvolvido com Vue3 e Bootstrap</p>
        </div>
        
        
    
    </div>    
  </div>
</template>

<script>
export default {
    data(){
        return{
            name: 'Footer'
        }
        
    }

}
</script>

<style scoped>
    li{
        list-style: none;
    }
    a{
        cursor: pointer;
        color: #F0CF99;
        padding: 10px 40px;
        font-size: 1em;
        text-decoration: none;
    }
    p{
        color: white;
        padding: 5px
    }
</style>