<template>
  <section>

    <div class="cl_header">
      <h1 class="cl_title">Palavra chave bem selecionada</h1>
      <h2 class="cl_subtitle">Subt. Palavra Chave</h2>
    </div>
 <!-- FIM DO CABEÇALHO-->

    <div class="cl_container">

        <div class="">

          <h2 class="cl_subtitle-two">Sobre Min</h2>
          <hr class="cl_divider">
        <div class="cl_about-me columns is-mobile is-multiline">

          <div class="column is-full-mobile is-full-tablet is-half-desktop">
          <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Pariatur excepturi labore tempore expedita, et iste tenetur suscipit explicabo! Dolores, aperiam non officia eos quod asperiores.Lorem ipsum dolor sit amet, consectetur adipisicing elit. Pariatur excepturi labore tempore expedita, et iste tenetur suscipit explicabo! Dolores, aperiam non officia eos quod asperiores
          </p>
          </div>

          <div class="column is-full-mobile is-full-tablet is-half-desktop">
            <img src="../favicon.png" >
          </div>

        </div>

      </div>
<!-- FIM DA SEÇÂO-->

      <div>
        
          <h2 class="cl_subtitle-two">Como Trabalho / O que Fazemos</h2>
          <hr class="cl_divider">

          <div class="cl_how-work columns is-mobile is-multiline">
            <div class="column is-full-mobile is-full-tablet is-one-third-desktop">

              <div>
                <h3>Cards com Titulo bem selecionado</h3>

                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Pariatur excepturi labore tempore expedita, et iste tenetur suscipit explicabo! Dolores, aperiam non officia eos quod asperiores.Lorem ipsum dolor sit amet, consectetur adipisicing elit. Pariatur excepturi labore tempore expedita, et iste tenetur suscipit explicabo! Dolores, aperiam non officia eos quod asperiores</p>
              </div>

            </div>

            <div class="column is-full-mobile is-full-tablet is-one-third-desktop">
              <div>
                <h3>Cards com Titulo bem selecionado</h3>
                
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Pariatur excepturi labore tempore expedita, et iste tenetur suscipit explicabo! Dolores, aperiam non officia eos quod asperiores.Lorem ipsum dolor sit amet, consectetur adipisicing elit. Pariatur excepturi labore tempore expedita, et iste tenetur suscipit explicabo! Dolores, aperiam non officia eos quod asperiores</p>
              </div>

            </div>

            <div class="column is-full-mobile is-full-tablet is-one-third-desktop">
              <div>
                <h3>Cards com Titulo bem selecionado</h3>
                
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Pariatur excepturi labore tempore expedita, et iste tenetur suscipit explicabo! Dolores, aperiam non officia eos quod asperiores.Lorem ipsum dolor sit amet, consectetur adipisicing elit. Pariatur excepturi labore tempore expedita, et iste tenetur suscipit explicabo! Dolores, aperiam non officia eos quod asperiores</p>
              </div>

            </div>
          </div>

      </div>

    </div>
<!-- FIM DA SEÇÂO-->

    <div class="cl_paralax">
      <h2 class="cl_subtitle-alternate">Frase transmitindo confiança no serviço</h2>
    </div>
<!-- FIM DA SEÇÂO-->

     <div class="cl_container">
        <h2 class="cl_subtitle-two">Portfólio</h2>
        <hr class="cl_divider"> 
        <p> Slider com fotos das logos dos sites e links para os mesmos</p>
        <div class="columns is-mobile is-multiline cl_portfolio">

            <div class="column is-full-mobile is-full-tablet is-one-fifth-desktop">
              <img src="../favicon.png">
            </div>

            <div class="column is-full-mobile is-full-tablet is-one-fifth-desktop">
              <img src="../favicon.png">
            </div>

            <div class="column is-full-mobile is-full-tablet is-one-fifth-desktop">
              <img src="../favicon.png">
            </div>

            <div class="column is-full-mobile is-full-tablet is-one-fifth-desktop">
              <img src="../favicon.png">
            </div>

            <div class="column is-full-mobile is-full-tablet is-one-fifth-desktop">
              <img src="../favicon.png">
            </div>

        </div>   

     </div>

     <footer class="cl_footer">
      <div class="cl_container">
        <img class="cl_footer-images" src="../favicon.png">
        <p class="cl_footer-paragraph">2020 © Mitchel TI. Todos os direitos reservados</p>
      </div>
    </footer>

  </section>
  
</template>

<script>
export default {
  metaInfo: {
    title: 'Mitchel TI'
  }
};
</script>

<style>
.home-links a {
  margin-right: 1rem;
}
.cl_about-me {
  display: flex;
  margin: auto; 
  justify-content: center;
  padding-top: 50px; 
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
.cl_how-work {
  display: flex;
  margin: auto;
  justify-content: center;
  padding-top: 50px; 
  padding-bottom: 100px; 
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
.cl_title {
  color: #FFF;
  font-size:35px
}
.cl_subtitle {
  color: #FFF;
  font-size: 25px
}
.cl_subtitle-two {
  color: #000;
  font-size: 25px;
  margin: auto;
  padding-top: 100px; 
  display: flex;
  justify-content: center;
}
.cl_subtitle-alternate {
  color: #fff;
  text-align: center;
  font-size: 40px;
}
.cl_header {
  background-image: url(/assets/img/back.jpg);
  height: 100%;
  background-attachment: fixed;
  padding: 400px 100px;
  background-position: center;
  background-size: cover;
}
</style>
