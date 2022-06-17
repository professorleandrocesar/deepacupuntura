<template>
  <div>
    <NavTopTwo/>
    <NavBottom/>
  

    <div class='main-tree'>
      <div>
        <h5><i class="fa-solid fa-circle-exclamation"></i> Sobre <br><br> Deep Acupuntura</h5>
      </div>
    </div>


    <div class='main-four'>
      <div class='main-four-card'>
        <p>
          Criado por Leandro Cesar Ramos da Costa, Deep Acupuntura é um clínica de medicina chinesa, para tratamento individualizado, que tem por objetivo tratar profundamente síndromes energéticas, através de sinais e sintomas de que o paciente relata e através de vários métodos de diagnósticos; podendo assim, traçar vários tipos de tratamentos, que só a medicina tradicional chinesa pode nos proporcionar, evitando a ingestão de medicamentos alopáticos, oferendo alternativas através de terapias totalmente seguras e naturais.
        </p>
      </div>
    </div>

    <div class='divider'></div>
    
    <div class='main-tree'>
      <div>
        <h5><i class="fa-solid fa-circle-exclamation"></i> Localização</h5>
      </div>
    </div>


    <div class='main-four'>
      <div class='main-four-card'>
        <p>
        Endereço: Rua da Conceição, 125 - Center Offices - sala: 1005 <br> Centro - Niterói -RJ - CEP: 24020-085        </p>
      </div>
      <iframe class='body-map' src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3675.5096784506004!2d-43.12292232898354!3d-22.89456440314661!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x9983b5d0974f89%3A0xd5dcb4494da04cac!2sDeep%20Acupuntura!5e0!3m2!1spt-BR!2sbr!4v1647055905172!5m2!1spt-BR!2sbr" style="border:0;" margin="auto;" allowfullscreen="" loading="lazy"></iframe>

    </div>

    <div class='divider'></div>

    <div class='main-tree'>
      <div>
        <h5><i class="fa-solid fa-circle-exclamation"></i> Leandro Cesar Ramos da Costa</h5>
      </div>
    </div>

    <div class='main-four'>
    <p>
              <i class="fas fa-graduation-cap"></i> Graduação em Educação Física - UNIVERSIDADE SALGADO DE OLIVEIRA - UNIVERSO (2005 - 2008);
              <br>
              <i class="fas fa-id-card"></i> CREF: 029260-G/RJ;
              <br>
              <i class="fas fa-certificate"></i> Pós-Graduação Lato-Sensu (especialização) em Acupuntura - UNIVERSIDADE CELSO LISBOA - UCL (2018 - 2022);
              <br>
              <i class="fas fa-certificate graduando"></i> Pós-Graduando em Cinesiologia, Biomecânica e Treinamento Físico - UNIVERSIDADE CASTELO BRANCO - UCB (2021 - atual);
              <br>
              <i class="fas fa-certificate graduando"></i> Pós-Graduando em Lesões e Doenças Musculoesqueléticas: Exercício Físico e Reabilitação - UNIVERSIDADE CASTELO BRANCO - UCB (2021 - atual);
            </p> 
            <ul class="main-l">
              <h5>Técnicas Ministradas:</h5>
              <i class="fas fa-chevron-right"></i> Acupuntura Sistêmica 
              <br>
              <i class="fas fa-chevron-right"></i> Craniopuntura
              <br>
              <i class="fas fa-chevron-right"></i> Ventosaterapia
              <br>
              <i class="fas fa-chevron-right"></i> Auriculoterapia 

            </ul>       
          <p class="nav-in"><i class="fas fa-link"></i> <a href="http://lattes.cnpq.br/3830820363501969" target="_blank">Currículo Lattes - CNPQ <i class="fas fa-external-link-alt"></i></a></p>
          </div>

          <h2 class="main-c">
          Acontecimentos <br> | linha do tempo |
        </h2>
        <div class='years'>
            <h4 class='dateYear'>|</h4>
            <h4 @click='doisDois' class='dateYear' :class='{ dateYearHover: aplicarTree }'>2022</h4>
            <h4 class='dateYear'>|</h4>
            <h4 @click='doisUm' class='dateYear' :class='{ dateYearHover: aplicar }'>2021</h4>
            <h4 class='dateYear'>|</h4>
            <h4 @click='umOito' class='dateYear' :class='{ dateYearHover: aplicarTwo }'>2018</h4>
            <h4 class='dateYear'>|</h4>
        <!--    
            <h4 @click='umUm' class='dateYear' :class='{ dateYearHover: aplicarFour }'>| 2011 |</h4>
            <h4 @click='zeroOito' class='dateYear' :class='{ dateYearHover: aplicarFive }'>| 2008 |</h4>
            <h4 @click='zeroCinco' class='dateYear' :class='{ dateYearHover: aplicarSix }'>| 2005 |</h4>
            <h4 @click='oitoSeis' class='dateYear' :class='{ dateYearHover: aplicarSeven }'>| 1986 |</h4>
        -->    
        </div>
        <br>
        <div v-html='acontecimentos'></div>
          <br>
          <br>
          <br>
          <br>


  </div>
</template>
<script>
export default {
  head: {
    title: 'Sobre | Deep Acupuntura',
    htmlAttrs: {
      lang: 'pt-br'
    },
    meta: [
      { charset: 'utf-8' },
      { name: 'viewport', content: 'width=device-width, initial-scale=1' },
      { hid: 'description', name: 'description', content: '' },
      { hid: 'keywords', name: 'description', content: 'Acupuntura' },
      { name: 'format-detection', content: 'telephone=no' },
      { name: 'msapplication-TileColor', content: '#860d0d' },
      { name: 'theme-color', content: '#860d0d' }
    ],
    link: [
      { rel: 'apple-touch-icon', size: '180x180', href: '/img/MyLogoBoldFundo.png' },
      { rel: 'icon', type: 'image/png', size: '32x32', href: '/img/MyLogoBoldFundo.png' },
      { rel: 'icon', type: 'image/png', size: '16x16', href: '/img/MyLogoBoldFundo.png' },
      { rel: 'apple-touch-icon', size: '180x180', href: '/img/apple-touch-icon.png' },
      { rel: 'manifest', href: '/img/site.webmanifest' },
      { rel: 'mask-icon', href: '/img/safari-pinned-tab.svg', color: '#860d0d' }
    ]
  },
  data() {
      return {
          aplicar : '',
          aplicarTwo : '',
          aplicarTree : 'true',
          aplicarFour : '',
          aplicarFive : '',
          aplicarSix : '',
          aplicarSeven : '',
          acontecimentos: `
          <h4>2022:</h4>
          <h4 style="text-align: left;"> Março</h4>
          <p class="main-l">
             <i class="fas fa-chevron-circle-right"></i> Inauguração da Clinica 'Deep Acupuntura' no Centro de Niteroi;
              <br>
            
          </p>
          <br>
          <h4 style="text-align: left;"> Fevereiro</h4>
          <p class="main-l">
             <i class="fas fa-chevron-circle-right"></i> Conlusão do curso de Pós-Graduação Lato-sensu em Acupuntura - Universidade Celso Lisboa - UCL;
              <br>
            <i class="fas fa-chevron-circle-right"></i> Finalizando o estágio em Acupuntura na Celso Lisboa - UCL;
            
          </p>
          <br>
          <h4 style="text-align: left;"> Janeiro</h4>
          <p class="main-l">
            <i class="fas fa-chevron-circle-right"></i> Curso de aprimoramento teórico e prático - Acupuntura Escalpiana de Jiao Shunfa;
            <br>
            <i class="fas fa-chevron-circle-right"></i> Site deepacupuntura.com no ar;
            
          </p>
          <br>
          
          `,
      }
  },
  methods: {
      doisDois() {
        this.aplicar = false,
          this.aplicarTwo = false,
          this.aplicarTree = true,
          this.aplicarFour = false,
          this.aplicarFive = false,
          this.aplicarSix = false,
          this.aplicarSeven = false,
          this.acontecimentos = 
          `
          <h4>2022:</h4>
          <h4 style="text-align: left;"> Março</h4>
          <p class="main-l">
             <i class="fas fa-chevron-circle-right"></i> Inauguração da Clinica 'Deep Acupuntura' no Centro de Niteroi;
              <br>
            
          </p>
          <br>
          <h4 style="text-align: left;"> Fevereiro</h4>
          <p class="main-l">
             <i class="fas fa-chevron-circle-right"></i> Conlusão do curso de Pós-Graduação Lato-sensu em Acupuntura - Universidade Celso Lisboa - UCL;
              <br>
            <i class="fas fa-chevron-circle-right"></i> Finalizando o estágio em Acupuntura na Celso Lisboa - UCL;
            
          </p>
          <br>
          <h4 style="text-align: left;"> Janeiro</h4>
          <p class="main-l">
            <i class="fas fa-chevron-circle-right"></i> Curso de aprimoramento teórico e prático - Acupuntura Escalpiana de Jiao Shunfa;
            <br>
            <i class="fas fa-chevron-circle-right"></i> Site deepacupuntura.com no ar;
            
          </p>
          <br>
          `
      },
      doisUm() {
          this.aplicar = true,
          this.aplicarTwo = false,
          this.aplicarTree = false,
          this.aplicarFour = false,
          this.aplicarFive = false,
          this.aplicarSix = false,
          this.aplicarSeven = false,
          this.acontecimentos = `
          <h4>2021:</h4>
          <h4 style="text-align: left;"> Julho</h4>
          <p class="main-l">
            <i class="fas fa-chevron-circle-right"></i> Início do curso de Pós-Graduação em Lesões e Doenças Musculoesqueléticas: Exercício Físico e Reabilitação - UCB;
            
          </p>
          <br>
        <h4 style="text-align: left;"> Fevereiro</h4>
          <p class="main-l">
             <i class="fas fa-chevron-circle-right"></i> Início do curso de Pós-Graduação em Cinesiologia, Biomecânica e Treinamento Físico - UCB;     
              <br>
            <i class="fas fa-chevron-circle-right"></i> Reinício do estágio em Acupuntura - Pós Pandemia (COVID-19);
            
          </p>
          <br>
          `
      },
      umOito(){
        this.aplicar = false,
          this.aplicarTwo = true,
          this.aplicarTree = false,
          this.aplicarFour = false,
          this.aplicarFive = false,
          this.aplicarSix = false,
          this.aplicarSeven = false,
          this.acontecimentos = `
          <h4>2018:</h4>
        <h4 style="text-align: left;">Novembro</h4>
          <p class="main-l">
            <i class="fas fa-chevron-circle-right"></i> Início do curso de Pós-Graduação em Acupuntura - Universidade Celso Lisboa - UCB;
            
          </p>
          <br>
          `
      },
      umUm(){
        this.aplicar = false,
          this.aplicarTwo = false,
          this.aplicarTree = false,
          this.aplicarFour = true,
          this.aplicarFive = false,
          this.aplicarSix = false,
          this.aplicarSeven = false,
          this.acontecimentos =
          `
          <h4>2011:</h4>
        <h4 style="text-align: left;">Novembro</h4>
          <ul class="main-l">
            <li>
              Conlusão do curso de Formação de Instrutor de Krav-Maga - Bukan School of Krav-maga - Rio de Janeiro - RJ;
            </li>
          </ul>
          <br>
        <h4 style="text-align: left;">Março</h4>
          <ul class="main-l">
            <li>
              Início do curso de Formação de Instrutor de Krav-Maga - Bukan School of Krav-maga - Rio de Janeiro - RJ;
            </li>
          </ul>
          <br>
          `
      },
      zeroOito(){
        this.aplicar = false,
          this.aplicarTwo = false,
          this.aplicarTree = false,
          this.aplicarFour = false,
          this.aplicarFive = true,
          this.aplicarSix = false,
          this.aplicarSeven = false,
          this.acontecimentos =
          `
          <h4>2008:</h4>
        <h4 style="text-align: left;">Fevereiro</h4>
          <ul class="main-l">
            <li>
              Conlusão do curso de Graduação em Educação Física - Universidade Salgado de Oliveita - UNIVERSO;
            </li>
          </ul>
          <br>
          `
      },
      zeroCinco() {
        this.aplicar = false,
          this.aplicarTwo = false,
          this.aplicarTree = false,
          this.aplicarFour = false,
          this.aplicarFive = false,
          this.aplicarSix = true,
          this.aplicarSeven = false,
          this.acontecimentos =
          `
          <h4>2005:</h4>
        <h4 style="text-align: left;">Fevereiro</h4>
          <ul class="main-l">
            <li>
              Início do curso de Graduação em Educação Física - Universidade Salgado de Oliveita - UNIVERSO;
            </li>
          </ul>
          <br>
          `
      },
      oitoSeis () {
        this.aplicar = false,
          this.aplicarTwo = false,
          this.aplicarTree = false,
          this.aplicarFour = false,
          this.aplicarFive = false,
          this.aplicarSix = false,
          this.aplicarSeven = true,
          this.acontecimentos = 
          `
          <h4>1986:</h4>
        <h4 style="text-align: left;">Outubro</h4>
          <ul class="main-l">
            <li>
              Nascimento no dia 08 - Neves - São Gonçalo - RJ;
            </li>
          </ul>
          <br>
          `
      }
  }
}
</script>

<style scoped>
a {
  text-decoration: none;
  color: #fff;
}

i {
  color: #fff;
  font-size: .9em;
  margin: auto;
}

code {
  font-size: 0.6em;
  padding-left: 10px;
  margin-left: 15px;
  margin-right: 60px;
  border-left: solid 5px #e23a28;
  color: #ddd;
}

.divider {
  height: 15px;
  background-color: #e23a2840;
}

.divider-ultimate {
  height: 30px;
  background-color: #860d0d;
}

.profile {
  background: #860d0d;
  display: flex;
  justify-content: flex-start;
  flex-wrap: wrap;
  padding: 20px 0 5px 0;
  margin-top: -10px;
}

.profile a {
  text-decoration: none;
  color: #fff;
  font-size: .9em;
}

.profile img {
  height: 70px;
  margin-left: 10px;
  padding: 0 25px 0 0;
}

.profile h1 {
  margin: 13px 0 -5px -10px;
  font-size: 1.5em;
  color: #fff;
}

.profile h4 {
  margin: 0 0 0 -10px;
  font-size: .9em;
  font-weight: 100;
  color: #e23a28;
}

.main-one {
  display: flex;
  justify-content: flex-start;
  flex-direction: column;
  padding: 10px 0 15px 0;
  box-shadow: 0px 10px 5px #ffffff90;
  background: #860d0d;
}

.main-one div {
  margin: 0 0 0 15px;
}

.main-one a:nth-child(1) i,
.main-one a:nth-child(2) i {
  padding-right: 3px;
  margin: 0 0 0 3px;
}

.main-one a:nth-child(2) i {
  padding-right: 4px;
  margin: 0 0 0 4px;
}

.main-one a:nth-child(3) i {
  margin: 0 0 0 3px;
  padding-right: 3px;
}

.main-one a {
  margin: 0 0 0 10px;
  color: #ddd;
}

.main-two {
  display: flex;
  justify-content: space-around;
  flex-direction: row;
  padding: 15px 0 18px 0;
  color: black;
  box-shadow: 0px 10px 20px #860d0d80;
  background: #860d0d;
  color: #fff;
}

.main-two a {
  margin: 20px 0 0 0px;
  color: #fff;
  font-weight: 600;
}

.main-two i {
  color: #fff;
  font-size: 1.1em;
  font-weight: 600;
}

.main-tree {
  display: flex;
  justify-content: flex-start;
  flex-direction: column;
  margin: 0px 0 0 0;
  color: #fff;
  background: #860d0d;
  overflow-x: auto;
}

.main-tree i {
  font-size: 1.2em;
  color: #fff;
}

.main-tree h5 {
  margin: 10px 0px 22px 10px;
}

.main-four {
  display: flex;
  justify-content: flex-start;
  flex-direction: column;
  margin: -10px 0 0 0;
  color: #fff;
  overflow-x: auto;
  box-shadow: 0px 10px 10px #ffffff30;
}

.main-four i {
  font-size: 1.2em;
  color: #555;
}

.main-four h5 {
  margin: 0 auto 20px auto;
}

.main-four-card {
  display: flex;
  justify-content: flex-start;
  flex-direction: row;
}

.main-four-card a {
  border: solid .1px #dddddd54;
  padding: 2px 6px;
  margin: 10px 4px;
  border-radius: 0% 10% 10% 10%;
}

.main-four-card span {
  position: relative;
  top: -6px;
  left: -14px;
}

.main-four-card h4 {
  margin: 0 0 0 15px;
  background: #92929240;
  padding: 0px 10px 0px 10px;
  border-radius: 12% 12% 12% 0%;
}

.main-four-card p {
  margin: 0 0 0 10px;
  font-size: .8em;
}

.main-five {
  background: #860d0d;
  display: flex;
  justify-content: flex-start;
  flex-direction: column;
  margin: -10px 0 0 0;
  color: #fff;
  box-shadow: 0px 10px 10px#bbb;
  overflow-x: auto;
}

.main-five i {
  font-size: 1.2em;
  color: #555;
}

.main-five h5 {
  margin-left: 10px;
}

.main-five-card {
  height: 370px;
  margin: 0 10px;
  border: solid .5px #fadb4190;
  display: flex;
  justify-content: flex-start;
  flex-direction: column;
}

.main-five-card a {
  border: solid .1px #dddddd54;
  margin: 0px 5px 20px 10px;
  width: 500px;
  border-radius: 3% 3% 3% 3%;
}

.main-five-card span {
  position: relative;
  top: -6px;
  left: -14px;
}

.main-five-card h4 {
  margin: 0 5px 0 10px;
}

.main-five-card p {
  margin: 0 0 0 10px;
  font-size: .8em;
}

.mini-profile {
  height: 25px;
  border-radius: 50%;
  margin: 10px 0 0 10px;
  padding: 0 15px 0 0;
}

.body-map {
  width: 300px;
  height: 300px;
  margin: 10px auto 100px auto;
}

a.nuxt-link-exact-active {
  background-color: #e23a2890;
  color: #fff;
  border-radius: 0% 10% 10% 10%;
}

@media only screen and (max-width: 369px) {}
</style>