<template>
  <div class="edrea_tm_section" id="about">
    <div class="section_inner">
      <div class="edrea_tm_about">
        <div class="left">
          <div class="image">
            <img src="img/thumbs/1-1.jpg" alt="" />
            <div class="main" data-img-url="img/about/profile2.jpeg"></div>
          </div>
        </div>
        <div class="right">
          <div class="short">
            <h3 class="name">Rafael <span class="coloring">Rodrigues</span></h3>
            <h3 class="job">
              <AnimationText />
            </h3>
          </div>
          <div class="text">
            <p>
              Olá, meu nome é <span>Rafael Rodrigues.</span>Sou formado em Análise
              e Desenvolvimento de Sistemas e Sistemas para Internet,
              concluindo a formação em 2022. Conto com 2 anos de
              experiência em desenvolvimento de software, durante os
              quais busquei constantemente aprimorar minhas
              habilidades e permanecer atualizado com as tendências
              tecnológicas do mercado. Destaco em minha trajetória a
              dedicação em contribuir para o crescimento e a inovação
              no campo do desenvolvimento de software.

            </p>
          </div>
          <div class="edrea_tm_button" id="aboutPopup">
            <a href="#">Ver mais...</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import AnimationText from "./AnimationText.vue";
export default {
  name: `AboutComponent`,
  data() {
    return {
      open: false,
    };
  },
  components: {
    AnimationText,
  },
};
</script>

<style scoped>
.edrea_tm_modalbox {
  top: -90px;
}
</style>
