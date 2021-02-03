<template>
  <div class="cl_header">
      <div class="cl_intro">
        <h1 class="cl_title">Palavra chave bem selecionada</h1>
        <h2 class="cl_subtitle">Subt. Palavra Chave</h2>
      </div>
    </div>
</template>

<script> 
export default {

};

</script>

<style>
.cl_header {
	background-image: url('../../../assets/images/back.jpg');
	height: 100vh;
	background-attachment: fixed;
	background-position: center;
	background-size: cover;
}
.cl_intro {
  position: absolute;
  top: 45%;
  left: 2rem;
}
.cl_title {
	color: #FFF;
	font-size:35px
}
.cl_subtitle {
	color: #FFF;
	font-size: 25px
}
</style>
