<template>
  <section>


    <Topnav></Topnav>
 <!-- FIM DO TOPNAV-->

    <Header></Header>
 <!-- FIM DO CABEÇALHO-->
    <div class="cl_container">
      
      <About></About>
    
<!-- FIM DA SEÇÂO-->
      <Work></Work>
      

    </div>
<!-- FIM DA SEÇÂO-->
  
    <div class="cl_paralax">
      <h2 class="cl_subtitle-alternate">Frase transmitindo confiança no serviço</h2>
    </div>
<!-- FIM DA SEÇÂO-->

     <div class="cl_container" id="portfolio">
        <Portfolio></Portfolio>
        
<!-- FIM DA SEÇÂO--> 
        <div id="recomendations">
          <h2 class="cl_subtitle-two">Recomendações de Clientes</h2>
          <hr class="cl_divider"> 

          <div class="columns is-mobile is-multiline cl_recomendations">
            <p class="cl_recomendation-parag">O que Pessoas disseram sobre meu trabalho/ recomendações.</p>
          </div>
        </div>
     </div>
<!-- FIM DA SEÇÂO-->

     <footer class="cl_footer">
      <div class="cl_container">
        <img class="cl_footer-images" src="../favicon-1.png">
        <p class="cl_footer-paragraph">2021 © Mitchel TI. Todos os direitos reservados</p>
      </div>
    </footer>
<!-- FIM DA SEÇÂO-->
  </section>
  
</template>

<script>

import Topnav     from '../components/ui/topnav/topnav.vue'
import Header     from '../components/ui/header/header.vue'
import About      from '../components/ui/about/about.vue'
import Work       from '../components/ui/work/work.vue'
import Portfolio  from '../components/ui/portfolio/portfolio.vue'

export default {
  metaInfo: {
    title: 'Mitchel TI'
  },
  components: {
    Topnav,
    Header,
    About,
    Work,
    Portfolio
  }, 

  data() {
    return {

    
      }
  }
};
</script>

<style>
.home-links a {
  margin-right: 1rem;
}

.cl_container {
  max-width: 1300px;
  margin: auto;
}
.cl_divider {
  width: 10%;
  background-color: #000;
  margin: 5px auto; 

}
.cl_footer {
  background-color: #1d1d1b;
  padding-top:100px;
}
.cl_footer-images {
  margin: auto;
  justify-content: center;
  display: flex;
  padding-bottom: 50px;
}
.cl_footer-paragraph {
  color: #fff;
  text-align: center;
  padding-bottom: 10px;
}


.cl_paralax {
  background-image: url('../assets/images/back2.jpg');
  height: 100%;
  background-attachment: fixed;
  padding: 100px 50px;
  background-position: center;
  background-size: cover;
}
.cl_portfolio {
  padding-top: 70px;
  padding-bottom: 70px;
}
.cl_recomendations {
  padding-top: 70px;
  padding-bottom: 70px;
}
.cl_recomendation-parag {
  margin: auto;
}


.cl_subtitle-alternate {
  color: #fff;
  text-align: center;
  font-size: 40px;
}

</style>
