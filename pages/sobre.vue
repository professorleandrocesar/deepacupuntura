<template>
  <div id='app'>
    <NavTopTwo />
    <NavBottom />
    <NavBottom />

    <div id="main">
      <div class="main-c"><i class="fas fasi fa-exclamation-circle"></i></div>
      <h1>Sobre</h1>
      <!-- <a href="sobre#teste">teste</a> -->
      <h2 class="main-c">
        Deep Acupuntura
      </h2>
      <h6 class='sub-h6'>| Tratando a raiz do seu problema |</h6>
      <p class='main-l'>
        <br>
        Criado por Leandro Cesar Ramos da Costa, <b class='emphasis-red'>Deep Acupuntura</b> é um clínica de medicina
        chinesa, para tratamento individualizado, que tem por objetivo tratar profundamente síndromes energéticas,
        através de sinais e sintomas de que o paciente relata e através de vários métodos de diagnósticos; podendo
        assim, traçar vários tipos de tratamentos, que só a medicina tradicional chinesa pode nos proporcionar,
        evitando a ingestão de medicamentos alopáticos, oferendo alternativas através de terapias totalmente seguras
        e naturais.

        <br>

      </p>
      <div class='contact'>
        <a href='https://api.whatsapp.com/send?phone=5521971305858%20&text=Olá,%20entrei%20no%20site%20do%20Deep%20Acupuntura,%20fiquei%20interessado(a)%20e%20gostaria%20de%20marcar%20uma%20Sessão%20de%20Terapia!%20Meu%20nome%20é'
          target='_blank'><i class="fab fa-whatsapp-square"></i></a>
        <a href='https://instagram.com/deepacupuntura' target='_blank'><i class="fab fa-instagram-square"></i></a>
        <a href='mailto:contato@deepacupuntura.com' target='_blank'><i class="fas fa-envelope-square"></i></a>
      </div>
      <div class="hr"></div>
      <br>
      <h3><i class="fas fa-map-marker-alt"></i> Localização</h3>
      <h3>INAUGURADO!!</h3>
      <div class='main-c wi'>
        <p>
          <p>Endereço: Rua da Conceição, 125 - Center Offices - sala: 1005 - Centro - Niterói -RJ - CEP: 24020-085</p>
        <br><iframe class='body-map'
          src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3675.5096784506004!2d-43.12292232898354!3d-22.89456440314661!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x9983b5d0974f89%3A0xd5dcb4494da04cac!2sDeep%20Acupuntura!5e0!3m2!1spt-BR!2sbr!4v1647055905172!5m2!1spt-BR!2sbr"
          style="border:0;" margin="auto;" allowfullscreen="" loading="lazy"></iframe>
        </p>
      </div>
      <br><br><br>
      <!--    
          <h4>Educação física</h4>
          <p class='main-l'>
          Há 15 anos no mercado, atuando na grande área da Educação Física, mais especificamente, no setor de musculação e atuando como personal trainer tem o interesse de 
          oferecer e mostrar seus serviços, ajudando pessoas com compromissos e resultados. <br>
          Sempre preocupado com sua formação ao longo dos anos, vem se dedicando aos estudos, na aréa da Cinesiologia e Biomecânica, buscando respaldos científicos, 
          evitando assim, o conhecimento empírico, que está em moda, junto com os famosos 'Youtubers'.
        </p>
    -->
      <div class="hr"></div>

      <!--<div class='terapia-image'><img src="img/myPhoto.png" alt=""></div> -->
      <h2 class="main-c">Leandro Cesar Ramos da Costa</h2>

      <!-- Colocar uma foto minha embaixo!! -->
      <!-- <div class="leandro-id">
            <img src="/src/assets/favicon.svg" alt="">
          </div> -->

      <p>
        <p class="main-l">
          <i class="fas fa-graduation-cap"></i> Graduação em Educação Física - UNIVERSIDADE SALGADO DE OLIVEIRA - UNIVERSO
        (2005 - 2008);
        <br>
        <i class="fas fa-id-card"></i> CREF: 029260-G/RJ;
        <br>
        <i class="fas fa-certificate"></i> Pós-Graduação Lato-Sensu (especialização) em Acupuntura - UNIVERSIDADE CELSO
        LISBOA - UCL (2018 - 2022);
        <br>
        <i class="fas fa-certificate graduando"></i> Pós-Graduando em Cinesiologia, Biomecânica e Treinamento Físico -
        UNIVERSIDADE CASTELO BRANCO - UCB (2021 - atual);
        <br>
        <i class="fas fa-certificate graduando"></i> Pós-Graduando em Lesões e Doenças Musculoesqueléticas: Exercício
        Físico e Reabilitação - UNIVERSIDADE CASTELO BRANCO - UCB (2021 - atual);
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
    </p>
      <p class="nav-in"><i class="fas fa-link"></i> <a href="http://lattes.cnpq.br/3830820363501969"
          target="_blank">Currículo Lattes - CNPQ <i class="fas fa-external-link-alt"></i></a></p>
      <br>
      <div class="hr"></div>
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
    </div>

    <!-- <div>
          <span class="nav-in dois-vinte-um">2021</span> | <span class="nav-in dois-vinte">2022</span>
        </div> -->
    <div class="output"></div>
  </div>
</template>

<script>
export default {
  head: {
    title: 'Sobre | Deep Acupuntura',
    meta: [
      {
        hid: 'description',
        name: 'description',
        content: ''
      },
      {
        hid: 'keywords',
        name: 'keywords',
        content: ''
      }
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

<!-- Add "scoped" attribute to limit CSS to this component only -->

