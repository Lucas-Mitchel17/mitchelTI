<template>
  <nav class="navbar is-fixed-top" role="navigation" aria-label="main navigation">
      <div class="navbar-brand">
        <a class="navbar-item" href="/">
          <img src="https://bulma.io/images/bulma-logo.png" width="112" height="28">
        </a>

        <a role="button" class="navbar-burger" :class="[{'is-active' : toggle }]"  @click="burger()" aria-label="menu" aria-expanded="false" data-target="navbarBasicExample">
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
        </a>
      </div>

      <div class="navbar-menu" :class="[{'is-active' : toggle }]">
        <div class="navbar-start">
          
        </div>

        <div class="navbar-end">
          <div class="navbar-item">
            <div class="buttons cl_itens-menu">
              <a class="navbar-item is-tab" href="#about">
                Sobre Min
              </a>

              <a class="navbar-item is-tab" href="#how-work">
                Como Trabalho
              </a>

              <a class="navbar-item is-tab" href="#portfolio">
                Portifólio
              </a>

              <a class="navbar-item is-tab" href="#recomendations">
                Recomendações
              </a>
            </div>
          </div>
        </div>
      </div>
    </nav>

</template>

<script> 
export default {
  methods: {
    burger() {
      this.toggle = !this.toggle;
    }
  }, 
  data() {
    return {
      toggle: false
    }
  }
};

</script>

<style>
  
  @media (max-width: 768px) {
    .cl_itens-menu {
      text-align: center;
      display: block;
    }
  }
</style>
