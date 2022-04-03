<template>
  <div>
      <NavTop/>
            <div id='befor-main'>
            <img src="/img/acu-index.jpg" alt="">
              <div id="main-index">
                  <p class='main-l viva-index'>VIVA MELHOR E TENHA MAIS SAÚDE COM</p>
                  <h3 class='main-l acupuntura-index'>Acupuntura</h3>
                  <p class='main-l conheca-index'>Conheça esta técnica milenar, natural e segura, para melhorar sua condição física,
                  mental e espiritual</p>
                  <a class='btn-agendar' href="https://api.whatsapp.com/send?phone=5521971305858%20&text=Leandro,%20quero%20marcar%20minha%20sess%C3%A3o!" target='_blank'><i class="fab fa-whatsapp"></i> Agendar</a>       
              </div>

      

            <br>
          <br>
          <h2 class='main-l-wi-tratamento'>TRATAMENTOS PARA
          
          </h2>
          <div class='main-l-trat'>
              <h4 @click='ansiedade()' class='dot-index' :class='{ selectTitleHover: aplicar }'  v-html='rAnsiedade'></h4>
              <h4 @click='depressao()' class='dot-index' :class='{ selectTitleHover: aplicarTwo }' v-html='rDepressao'></h4>
              <h4 @click='estresse()' class='dot-index' :class='{ selectTitleHover: aplicarFive }' v-html='rEstresse'></h4>
              <h4 @click='cervicalgia()' class='dot-index' :class='{ selectTitleHover: aplicarTree }' v-html='rCervicalgia'></h4>
              <h4 @click='lombalgia()' class='dot-index' :class='{ selectTitleHover: aplicarFour }' v-html='rLombalgia'></h4>
              <h4 @click='enxaqueca()' class='dot-index' :class='{ selectTitleHover: aplicarSix }' v-html='rEnxaqueca'></h4>
              <h4 @click='cefaleia()' class='dot-index' :class='{ selectTitleHover: aplicarSeven }' v-html='rCefaleia'></h4>
              <h4 @click='baixaImunidade()' class='dot-index' :class='{ selectTitleHover: aplicarEight }' v-html='rBaixaImunidade'></h4>
              <h4 @click='burnOut()' class='dot-index' :class='{ selectTitleHover: aplicarNine }' v-html='rBurnout'></h4>
              <h4 @click='laringite()' class='dot-index' :class='{ selectTitleHover: aplicarTen }' v-html='rLaringite'></h4>
              <h4 @click='insonia()' class='dot-index' :class='{ selectTitleHover: aplicarEleven }' v-html='rInsonia'></h4>
              <h4 @click='zumbido()' class='dot-index' :class='{ selectTitleHover: aplicarTwelve }' v-html='rZumbido'></h4>
              <h4 @click='labirintite()' class='dot-index' :class='{ selectTitleHover: aplicarThirteen }' v-html='rLabirintite'></h4>
              <h4 @click='sinusite()' class='dot-index' :class='{ selectTitleHover: aplicarFourteen }' v-html='rSinusite'></h4>
              <!--Distúrbios ginecológicos
                  Distúrbios gastrointestinais
                  Distúrbios alérgicos
                  Distúrbios imunológicos -->
            </div>
              <h5></h5>
          </div>
            <h2 class='main-l-wi-escolha'>TERAPIAS + INDICADAS</h2>
            <div class='homeTwo'>
              <div class='homeTwoDot' :class='{ selectTitle: aplicarAcu }'><nuxt-link to="/terapias">Acupuntura Sistêmica</nuxt-link> </div>
              <div class='homeTwoDot' :class='{ selectTitle: aplicarCran }'><nuxt-link to="/terapias">Craniopuntura</nuxt-link> </div>
              <div class='homeTwoDot' :class='{ selectTitle: aplicarCran }'><nuxt-link to="/terapias">Auriculoterapia</nuxt-link> </div>
              <div class='homeTwoDot' :class='{ selectTitle: aplicarCran }'><nuxt-link to="/terapias">Ventosaterapia</nuxt-link> </div>
              <!--
              // <div @click='acupuntura()' class='homeTwoDot' :class='{ selectTitle: aplicarAcu }'>Acupuntura Sistêmica</div>
              // <div @click='craniopuntura()' class='homeTwoDot' :class='{ selectTitle: aplicarCran }'>Craniopuntura</div>
              // <div @click='auriculo()' class='homeTwoDot' :class='{ selectTitle: aplicarAur }'>Auriculoterapia</div>
              // <div @click='ventosa()' class='homeTwoDot' :class='{ selectTitle: aplicarVen }'>Ventosaterapia</div>
              -->
            </div>
      <div id='main-white'><br>
        <h3 style='text-transform: uppercase;'>INAUGURADO!!</h3>
      <br>
      </div>
      <div id='main-white'><br>
      <div class='back-white'> 
      <h1><i class="fas fa-map-marker-alt"></i> Localização</h1>
      <div class='main-c wi'>
          <p>
          <h3>Deep Acupuntura</h3><p>Endereço: Rua da Conceição, 125 - Center Offices - sala: 1005 - Centro - Niterói -RJ - CEP: 24020-085</p><br><iframe class='body-map' src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3675.5096784506004!2d-43.12292232898354!3d-22.89456440314661!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x9983b5d0974f89%3A0xd5dcb4494da04cac!2sDeep%20Acupuntura!5e0!3m2!1spt-BR!2sbr!4v1647055905172!5m2!1spt-BR!2sbr" style="border:0;" margin="auto;" allowfullscreen="" loading="lazy"></iframe>
          </div>
      </div>
      <br><br>
          

      </div>
        <div class='contact'>
          <a href='https://api.whatsapp.com/send?phone=5521971305858%20&text=Olá,%20entrei%20no%20site%20do%20Deep%20Acupuntura,%20fiquei%20interessado(a)%20e%20gostaria%20de%20marcar%20uma%20Sessão%20de%20Terapia!%20Meu%20nome%20é'  target='_blank'><i class="fab fa-whatsapp-square"></i></a> 
          <a href='https://instagram.com/deepacupuntura' target='_blank'><i class="fab fa-instagram-square"></i></a>
          <a href='mailto:contato@deepacupuntura.com' target='_blank'><i class="fas fa-envelope-square"></i></a>
        </div>
          <br><br><br><br>
  </div>
</template>
<script>
export default {
  head: {
    title: 'Deep Acupuntura',
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
          // <p class='main-j'>
          
          // </p>
          // <br>
  data() {
      return {
          aplicar : '',
          output: '',
          aplicarAcu: '',
          aplicarAur: '',
          aplicarVen: '',
          aplicarCran: '',
          aplicarAcu: '',
          aplicarAur: '',
          aplicarVen: '',
          aplicar: '',
          aplicarTwo: '',
          aplicarTree: '',
          aplicarFour: '',
          aplicarFive: '',
          aplicarSix: '',
          aplicarSeven: '',
          aplicarEight: '',
          aplicarNine: '',
          aplicarTen: '',
          aplicarEleven: '',
          aplicarTwelve: '',
          aplicarThirteen:'' ,
          aplicarFourteen: '',
          rAnsiedade:'Ansiedade',
          rDepressao:'Depressão',
          rEstresse:'Estresse',
          rCervicalgia:'Cervicalgia',
          rLombalgia: 'Lombalgia',
          rEnxaqueca: 'Enxaqueca',
          rCefaleia:'Cefaleia',
          rBaixaImunidade:'Baixa Imunidade',
          rBurnout:'Burnout',
          rLaringite:'Laringite',
          rInsonia:'Insônia',
          rZumbido:'Zumbido',
          rLabirintite:'Labirintite',
          rSinusite:'Sinusite',

      }
  },
  methods: {
    acupuntura() {
          this.aplicarAcu = true,
          this.aplicarAur = false,
          this.aplicarVen = false,
          this.aplicarCran = false,
          this.aplicar = true,
          this.aplicarTwo = true,
          this.aplicarTree = true,
          this.aplicarFour = true,
          this.aplicarFive = true,
          this.aplicarSix = true,
          this.aplicarSeven = true,
          this.aplicarEight = true,
          this.aplicarNine = true,
          this.aplicarTen = true,
          this.aplicarEleven = true,
          this.aplicarTwelve = true,
          this.aplicarThirteen = true,
          this.aplicarFourteen = true,
          this.rAnsiedade = 'ansiedade',
          this.rDepressao = 'Depressão',
          this.rEstresse='Estresse',
          this.rCervicalgia='Cervicalgia',
          this.rLombalgia= 'Lombalgia',
          this.rEnxaqueca= 'Enxaqueca',
          this.rCefaleia='Cefaleia',
          this.rBaixaImunidade='Baixa Imunidade',
          this.rBurnout='Burnout',
          this.rLaringite='Laringite',
          this.rInsonia='Insônia',
          this.rZumbido='Zumbido',
          this.rLabirintite='Labirintite',
          this.rSinusite='Sinusite'
    },
    craniopuntura() {
          this.aplicarAcu = false,
          this.aplicarAur = false,
          this.aplicarVen = false,
          this.aplicarCran = true,
          this.aplicar = true,
          this.aplicarTwo = true,
          this.aplicarTree = true,
          this.aplicarFour = true,
          this.aplicarFive = true,
          this.aplicarSix = true,
          this.aplicarSeven = true,
          this.aplicarCran = true,
          this.aplicarEight = true,
          this.aplicarNine = true,
          this.aplicarTen = true,
          this.aplicarEleven = true,
          this.aplicarCran = true,
          this.aplicarTwelve = true,
          this.aplicarThirteen = true,
          this.aplicarFourteen = true,
          this.rAnsiedade = 'ansiedade',
          this.rDepressao = 'Depressão',
          this.rEstresse='Estresse',
          this.rCervicalgia='Cervicalgia',
          this.rLombalgia= 'Lombalgia',
          this.rEnxaqueca= 'Enxaqueca',
          this.rCefaleia='Cefaleia',
          this.rBaixaImunidade='Baixa Imunidade',
          this.rBurnout='Burnout',
          this.rLaringite='Laringite',
          this.rInsonia='Insônia',
          this.rZumbido='Zumbido',
          this.rLabirintite='Labirintite',
          this.rSinusite='Sinusite'
    },

    auriculo() {
          this.aplicarAur = true,
          this.aplicarAcu = false,
          this.aplicarVen = false,
          this.aplicar = true,
          this.aplicarCran = false,
          this.aplicarTwo = true,
          this.aplicarTree = true,
          this.aplicarFour = true,
          this.aplicarFive = true,
          this.aplicarSix = true,
          this.aplicarSeven = true,
          this.aplicarEight = true,
          this.aplicarNine = true,
          this.aplicarTen = true,
          this.aplicarEleven = true,
          this.aplicarTwelve = true,
          this.aplicarThirteen = true,
          this.aplicarFourteen = true,
          this.rAnsiedade = 'ansiedade',
          this.rDepressao = 'Depressão',
          this.rEstresse='Estresse',
          this.rCervicalgia='Cervicalgia',
          this.rLombalgia= 'Lombalgia',
          this.rEnxaqueca= 'Enxaqueca',
          this.rCefaleia='Cefaleia',
          this.rBaixaImunidade='Baixa Imunidade',
          this.rBurnout='Burnout',
          this.rLaringite='Laringite',
          this.rInsonia='Insônia',
          this.rZumbido='Zumbido',
          this.rLabirintite='Labirintite',
          this.rSinusite='Sinusite'
    },
    ventosa() {
          this.aplicarVen = true,
          this.aplicarCran = true,
          this.aplicarAcu = false,
          this.aplicarAur = false,
          this.aplicar = false,
          this.aplicarCran = false,
          this.aplicarTwo = false,
          this.aplicarTree = true,
          this.aplicarFour = true,
          this.aplicarFive = false,
          this.aplicarSix = false,
          this.aplicarSeven = false,
          this.aplicarEight = false,
          this.aplicarNine = false,
          this.aplicarTen = false,
          this.aplicarEleven = false,
          this.aplicarTwelve = false,
          this.aplicarThirteen = false,
          this.aplicarFourteen = false,
          this.rAnsiedade = 'ansiedade',
          this.rDepressao = 'Depressão',
          this.rEstresse='Estresse',
          this.rCervicalgia='Cervicalgia',
          this.rLombalgia= 'Lombalgia',
          this.rEnxaqueca= 'Enxaqueca',
          this.rCefaleia='Cefaleia',
          this.rBaixaImunidade='Baixa Imunidade',
          this.rBurnout='Burnout',
          this.rLaringite='Laringite',
          this.rInsonia='Insônia',
          this.rZumbido='Zumbido',
          this.rLabirintite='Labirintite',
          this.rSinusite='Sinusite'
    },

      ansiedade() {
          this.aplicarAcu = true,
          this.aplicarAur = true,
          this.aplicarCran = false,
          this.aplicarVen = false,
          this.aplicar = true,
          this.aplicarTwo = false,
          this.aplicarTree = false,
          this.aplicarFour = false,
          this.aplicarFive = false,
          this.aplicarSix = false,
          this.aplicarSeven = false,
          this.aplicarEight = false,
          this.aplicarNine = false,
          this.aplicarTen = false,
          this.aplicarEleven = false,
          this.aplicarTwelve = false,
          this.aplicarThirteen = false,
          this.aplicarFourteen = false,
          this.rDepressao = 'depressão',
          this.rAnsiedade = `<span><h4>Ansiedade</h4></span>
          <br>
          <span class='white'>é um sentimento de inquietação e preocupação, geralmente generalizado e sem foco, 
          como uma reação exagerada a uma situação que é apenas subjetivamente vista como ameaçadora.</span>`,
          this.rEstresse='Estresse',
          this.rCervicalgia='Cervicalgia',
          this.rLombalgia= 'Lombalgia',
          this.rEnxaqueca= 'Enxaqueca',
          this.rCefaleia='Cefaleia',
          this.rBaixaImunidade='Baixa Imunidade',
          this.rBurnout='Burnout',
          this.rLaringite='Laringite',
          this.rInsonia='Insônia',
          this.rZumbido='Zumbido',
          this.rLabirintite='Labirintite',
          this.rSinusite='Sinusite'
      },
      depressao(){
          this.aplicarAcu = true,
          this.aplicarAur = false,
          this.aplicarVen = false,
          this.aplicarCran = true,
          this.aplicar = false,
          this.aplicarTwo = true,
          this.aplicarTree = false,
          this.aplicarFour = false,
          this.aplicarFive = false,
          this.aplicarSix = false,
          this.aplicarSeven = false,
          this.aplicarEight = false,
          this.aplicarNine = false,
          this.aplicarTen = false,
          this.aplicarEleven = false,
          this.aplicarTwelve = false,
          this.aplicarThirteen = false,
          this.aplicarFourteen = false,
          this.rAnsiedade = 'ansiedade',
          this.rDepressao = `<span><h4>Depressão</h4></span>
          <br>
          <span class='white'>é um transtorno mental caracterizado por tristeza profunda persistente 
          e aversão a atividades. Pode afetar os pensamentos, comportamentos, sentimentos e o bem-estar de uma pessoa.</span>`,
          this.rEstresse='Estresse',
          this.rCervicalgia='Cervicalgia',
          this.rLombalgia= 'Lombalgia',
          this.rEnxaqueca= 'Enxaqueca',
          this.rCefaleia='Cefaleia',
          this.rBaixaImunidade='Baixa Imunidade',
          this.rBurnout='Burnout',
          this.rLaringite='Laringite',
          this.rInsonia='Insônia',
          this.rZumbido='Zumbido',
          this.rLabirintite='Labirintite',
          this.rSinusite='Sinusite'
      },
      estresse() {
          this.aplicarAcu = true,
          this.aplicarAur = true,
          this.aplicarVen = false,
          this.aplicarTwo = false,
          this.aplicarCran = false,
          this.aplicar = false,
          this.aplicarTree = false,
          this.aplicarFour = false,
          this.aplicarFive = true,
          this.aplicarSix = false,
          this.aplicarSeven = false,
          this.aplicarEight = false,
          this.aplicarNine = false,
          this.aplicarTen = false,
          this.aplicarEleven = false,
          this.aplicarTwelve = false,
          this.aplicarThirteen = false,
          this.aplicarFourteen = false,
          this.rAnsiedade = 'ansiedade',
          this.rDepressao = 'Depressão',
          this.rEstresse=`<span><h4>Estresse</h4></span>
          <br>
          <span class='white'>É causado pela ansiedade e pela depressão devido à mudança brusca no 
          estilo de vida e a exposição a um determinado ambiente, que leva a pessoa a sentir um determinado tipo de angústia. </span>`,
          this.rCervicalgia='Cervicalgia',
          this.rLombalgia= 'Lombalgia',
          this.rEnxaqueca= 'Enxaqueca',
          this.rCefaleia='Cefaleia',
          this.rBaixaImunidade='Baixa Imunidade',
          this.rBurnout='Burnout',
          this.rLaringite='Laringite',
          this.rInsonia='Insônia',
          this.rZumbido='Zumbido',
          this.rLabirintite='Labirintite',
          this.rSinusite='Sinusite'
      },
      cervicalgia(){
          this.aplicarAcu = true,
          this.aplicarAur = true,
          this.aplicarVen = true,
          this.aplicar = false,
          this.aplicarCran = false,
          this.aplicarTwo = false,
          this.aplicarTree = true,
          this.aplicarFour = false,
          this.aplicarFive = false,
          this.aplicarSix = false,
          this.aplicarSeven = false,
          this.aplicarEight = false,
          this.aplicarNine = false,
          this.aplicarTen = false,
          this.aplicarEleven = false,
          this.aplicarTwelve = false,
          this.aplicarThirteen = false,
          this.aplicarFourteen = false,
          this.rAnsiedade = 'ansiedade',
          this.rDepressao = 'Depressão',
          this.rEstresse='Estresse',
          this.rCervicalgia=`<span><h4>Cervicalgia</h4></span>
          <br>
          <span class='white'>Dor no pescoço e ombro que varia em intensidade, podendo ser incômoda ou 
          como um choque elétrico desde o pescoço até o braço.</span>`,
          this.rLombalgia= 'Lombalgia',
          this.rEnxaqueca= 'Enxaqueca',
          this.rCefaleia='Cefaleia',
          this.rBaixaImunidade='Baixa Imunidade',
          this.rBurnout='Burnout',
          this.rLaringite='Laringite',
          this.rInsonia='Insônia',
          this.rZumbido='Zumbido',
          this.rLabirintite='Labirintite',
          this.rSinusite='Sinusite'
      },
      lombalgia(){
          this.aplicarAcu = true,
          this.aplicarAur = true,
          this.aplicarVen = true,
          this.aplicarCran = true,
          this.aplicar = false,
          this.aplicarTwo = false,
          this.aplicarTree = false,
          this.aplicarFour = true,
          this.aplicarFive = false,
          this.aplicarSix = false,
          this.aplicarSeven = false,
          this.aplicarEight = false,
          this.aplicarNine = false,
          this.aplicarTen = false,
          this.aplicarEleven = false,
          this.aplicarTwelve = false,
          this.aplicarThirteen = false,
          this.aplicarFourteen = false,
          this.rAnsiedade = 'ansiedade',
          this.rDepressao = 'Depressão',
          this.rEstresse='Estresse',
          this.rCervicalgia='Cervicalgia',
          this.rLombalgia= `<span><h4>Lombalgia</h4></span>
          <br>
          <span class='white'>Uma condição dolorosa comum que afeta a parte inferior da coluna.
A dor lombar é causada por uma lesão em um músculo (tensão) ou ligamento (entorse). As causas comuns incluem 
levantamento impróprio, má postura, falta de exercícios físicos regulares, fratura, disco rompido ou artrite.</span>`,
          this.rEnxaqueca= 'Enxaqueca',
          this.rCefaleia='Cefaleia',
          this.rBaixaImunidade='Baixa Imunidade',
          this.rBurnout='Burnout',
          this.rLaringite='Laringite',
          this.rInsonia='Insônia',
          this.rZumbido='Zumbido',
          this.rLabirintite='Labirintite',
          this.rSinusite='Sinusite'
      },
      enxaqueca() {
          this.aplicarAcu = true,
          this.aplicarAur = false,
          this.aplicarVen = false,
          this.aplicarCran = true,
          this.aplicar = false,
          this.aplicarTwo = false,
          this.aplicarTree = false,
          this.aplicarFour = false,
          this.aplicarFive = false,
          this.aplicarSix = true,
          this.aplicarSeven = false,
          this.aplicarEight = false,
          this.aplicarNine = false,
          this.aplicarTen = false,
          this.aplicarEleven = false,
          this.aplicarTwelve = false,
          this.aplicarThirteen = false,
          this.aplicarFourteen = false,
          this.rAnsiedade = 'ansiedade',
          this.rDepressao = 'Depressão',
          this.rEstresse='Estresse',
          this.rCervicalgia='Cervicalgia',
          this.rLombalgia= 'Lombalgia',
          this.rEnxaqueca= `<span><h4>Enxaqueca</h4></span>
          <br>
          <span class='white'>Dor de cabeça de intensidade variável, muitas vezes acompanhada de náuseas e sensibilidade à luz e ao som.
Às vezes, as enxaquecas são precedidas por sintomas de alerta. Os gatilhos incluem alterações hormonais, certos alimentos e bebidas, estresse 
e exercícios físicos.</span>`,
          this.rCefaleia='Cefaleia',
          this.rBaixaImunidade='Baixa Imunidade',
          this.rBurnout='Burnout',
          this.rLaringite='Laringite',
          this.rInsonia='Insônia',
          this.rZumbido='Zumbido',
          this.rLabirintite='Labirintite',
          this.rSinusite='Sinusite'
      },
      cefaleia () {
          this.aplicarAcu = true,
          this.aplicarAur = true,
          this.aplicarVen = false,
          this.aplicar = false,
          this.aplicarTwo = false,
          this.aplicarTree = false,
          this.aplicarFour = false,
          this.aplicarFive = false,
          this.aplicarSix = false,
          this.aplicarSeven = true,
          this.aplicarCran = true,
          this.aplicarEight = false,
          this.aplicarNine = false,
          this.aplicarTen = false,
          this.aplicarEleven = false,
          this.aplicarTwelve = false,
          this.aplicarThirteen = false,
          this.aplicarFourteen = false,
          this.rAnsiedade = 'ansiedade',
          this.rDepressao = 'Depressão',
          this.rEstresse='Estresse',
          this.rCervicalgia='Cervicalgia',
          this.rLombalgia= 'Lombalgia',
          this.rEnxaqueca= 'Enxaqueca',
          this.rCefaleia=`<span><h4>Cefaléia</h4></span>
          <br>
          <span class='white'>Uma sensação dolorosa em qualquer parte da cabeça, 
          desde aguda até incômoda, podendo ocorrer junto com outros sintomas.</span>`,
          this.rBaixaImunidade='Baixa Imunidade',
          this.rBurnout='Burnout',
          this.rLaringite='Laringite',
          this.rInsonia='Insônia',
          this.rZumbido='Zumbido',
          this.rLabirintite='Labirintite',
          this.rSinusite='Sinusite'
      },
      baixaImunidade () {
          this.aplicarAcu = true,
          this.aplicarAur = false,
          this.aplicarVen = false,
          this.aplicarCran = false,
          this.aplicar = false,
          this.aplicarTwo = false,
          this.aplicarTree = false,
          this.aplicarFour = false,
          this.aplicarFive = false,
          this.aplicarSix = false,
          this.aplicarSeven = false,
          this.aplicarEight = true,
          this.aplicarNine = false,
          this.aplicarTen = false,
          this.aplicarEleven = false,
          this.aplicarTwelve = false,
          this.aplicarThirteen = false,
          this.aplicarFourteen = false,
          this.rAnsiedade = 'ansiedade',
          this.rDepressao = 'Depressão',
          this.rEstresse='Estresse',
          this.rCervicalgia='Cervicalgia',
          this.rLombalgia= 'Lombalgia',
          this.rEnxaqueca= 'Enxaqueca',
          this.rCefaleia='Cefaleia',
          this.rBaixaImunidade=`<span><h4>Baixa Imunidade</h4></span>
          <br>
          <span class='white'>pode ser percebida quando o organismo dá alguns sinais, indicando que as defesas do organismo estão baixas e que o sistema imunológico não está sendo capaz de combater 
          os agentes infecciosos, como vírus e bactérias, o que pode fazer com que a pessoa fique doente com mais frequência.</span>`,
          this.rBurnout='Burnout',
          this.rLaringite='Laringite',
          this.rInsonia='Insônia',
          this.rZumbido='Zumbido',
          this.rLabirintite='Labirintite',
          this.rSinusite='Sinusite'
      },
      burnOut() {
          this.aplicarAcu = true,
          this.aplicarAur = false,
          this.aplicarVen = false,
          this.aplicarCran = true,
          this.aplicar = false,
          this.aplicarTwo = false,
          this.aplicarTree = false,
          this.aplicarFour = false,
          this.aplicarFive = false,
          this.aplicarSix = false,
          this.aplicarSeven = false,
          this.aplicarEight = false,
          this.aplicarNine = true,
          this.aplicarTen = false,
          this.aplicarEleven = false,
          this.aplicarTwelve = false,
          this.aplicarThirteen = false,
          this.aplicarFourteen = false,
          this.rAnsiedade = 'ansiedade',
          this.rDepressao = 'Depressão',
          this.rEstresse='Estresse',
          this.rCervicalgia='Cervicalgia',
          this.rLombalgia= 'Lombalgia',
          this.rEnxaqueca= 'Enxaqueca',
          this.rCefaleia='Cefaleia',
          this.rBaixaImunidade='Baixa Imunidade',
          this.rBurnout=`<span><h4>Burnout</h4></span>
          <br>
          <span class='white'>A síndrome de burnout é um distúrbio psíquico causado pela exaustão extrema, sempre relacionada ao trabalho de um indivíduo. Essa condição 
          também é chamada de “síndrome do esgotamento profissional” e afeta quase todas as facetas da vida de um indivíduo.</span>`,
          this.rLaringite='Laringite',
          this.rInsonia='Insônia',
          this.rZumbido='Zumbido',
          this.rLabirintite='Labirintite',
          this.rSinusite='Sinusite'
      },
      laringite() {
          this.aplicarAcu = true,
          this.aplicarAur = true,
          this.aplicarVen = false,
          this.aplicarCran = true,
          this.aplicar = false,
          this.aplicarTwo = false,
          this.aplicarTree = false,
          this.aplicarFour = false,
          this.aplicarFive = false,
          this.aplicarSix = false,
          this.aplicarSeven = false,
          this.aplicarEight = false,
          this.aplicarNine = false,
          this.aplicarTen = true,
          this.aplicarEleven = false,
          this.aplicarTwelve = false,
          this.aplicarThirteen = false,
          this.aplicarFourteen = false,
          this.rAnsiedade = 'ansiedade',
          this.rDepressao = 'Depressão',
          this.rEstresse='Estresse',
          this.rCervicalgia='Cervicalgia',
          this.rLombalgia= 'Lombalgia',
          this.rEnxaqueca= 'Enxaqueca',
          this.rCefaleia='Cefaleia',
          this.rBaixaImunidade='Baixa Imunidade',
          this.rBurnout='Burnout',
          this.rLaringite=`<span><h4>Laringite</h4></span>
          <br>
          <span class='white'>é a inflamação da laringe (região das vias aéreas onde ficam localizadas as cordas vocais), que conecta a faringe à traqueia e faz parte do sistema respiratório. A inflamação 
          dessa região pode ser causada por vírus (mais prevalente), bactérias, inalação de agentes alérgicos ou esforço excessivo da voz.</span>`,
          this.rInsonia='Insônia',
          this.rZumbido='Zumbido',
          this.rLabirintite='Labirintite',
          this.rSinusite='Sinusite'
      },
      insonia() {
          this.aplicarAcu = true,
          this.aplicarAur = false,
          this.aplicarVen = false,
          this.aplicar = false,
          this.aplicarTwo = false,
          this.aplicarTree = false,
          this.aplicarFour = false,
          this.aplicarFive = false,
          this.aplicarSix = false,
          this.aplicarSeven = false,
          this.aplicarEight = false,
          this.aplicarNine = false,
          this.aplicarTen = false,
          this.aplicarEleven = true,
          this.aplicarCran = true,
          this.aplicarTwelve = false,
          this.aplicarThirteen = false,
          this.aplicarFourteen = false,
          this.rAnsiedade = 'ansiedade',
          this.rDepressao = 'Depressão',
          this.rEstresse='Estresse',
          this.rCervicalgia='Cervicalgia',
          this.rLombalgia= 'Lombalgia',
          this.rEnxaqueca= 'Enxaqueca',
          this.rCefaleia='Cefaleia',
          this.rBaixaImunidade='Baixa Imunidade',
          this.rBurnout='Burnout',
          this.rLaringite='Laringite',
          this.rInsonia=`<span><h4>Insônia</h4></span>
          <br>
          <span class='white'>é caracterizada pela dificuldade de dormir ou conseguir manter um sono contínuo sem ser interrompido durante a noite. Cerca de 30% a 50% dos brasileiros sofrem com a insônia, 
          que pode se manifestar por diversas razões, como estresse, ansiedade, depressão, dor crônica e uso de certos medicamentos.</span>`,
          this.rZumbido='Zumbido',
          this.rLabirintite='Labirintite',
          this.rSinusite='Sinusite'
      },
      zumbido() {
          this.aplicarAcu = true,
          this.aplicarAur = false,
          this.aplicarVen = false,
          this.aplicarCran = true,
          this.aplicar = false,
          this.aplicarTwo = false,
          this.aplicarTree = false,
          this.aplicarFour = false,
          this.aplicarFive = false,
          this.aplicarSix = false,
          this.aplicarSeven = false,
          this.aplicarEight = false,
          this.aplicarNine = false,
          this.aplicarTen = false,
          this.aplicarEleven = false,
          this.aplicarTwelve = true,
          this.aplicarThirteen = false,
          this.aplicarFourteen = false,
          this.rAnsiedade = 'ansiedade',
          this.rDepressao = 'Depressão',
          this.rEstresse='Estresse',
          this.rCervicalgia='Cervicalgia',
          this.rLombalgia= 'Lombalgia',
          this.rEnxaqueca= 'Enxaqueca',
          this.rCefaleia='Cefaleia',
          this.rBaixaImunidade='Baixa Imunidade',
          this.rBurnout='Burnout',
          this.rLaringite='Laringite',
          this.rInsonia='Insônia',
          this.rZumbido=`<span><h4>Zumbido</h4></span>
          <br>
          <span class='white'>Também chamado de Sibilo ou Tinido, pode ser definido como uma ilusão auditiva, ou seja, uma sensação sonora não relacionada com uma fonte externa de estimulação.</span>`,
          this.rLabirintite='Labirintite',
          this.rSinusite='Sinusite'
      },
      labirintite() {
          this.aplicarAcu = true,
          this.aplicarAur = false,
          this.aplicarVen = false,
          this.aplicarCran = true,
          this.aplicar = false,
          this.aplicarTwo = false,
          this.aplicarTree = false,
          this.aplicarFour = false,
          this.aplicarFive = false,
          this.aplicarSix = false,
          this.aplicarSeven = false,
          this.aplicarEight = false,
          this.aplicarNine = false,
          this.aplicarTen = false,
          this.aplicarEleven = false,
          this.aplicarTwelve = false,
          this.aplicarThirteen = true,
          this.aplicarFourteen = false,
          this.rAnsiedade = 'ansiedade',
          this.rDepressao = 'Depressão',
          this.rEstresse='Estresse',
          this.rCervicalgia='Cervicalgia',
          this.rLombalgia= 'Lombalgia',
          this.rEnxaqueca= 'Enxaqueca',
          this.rCefaleia='Cefaleia',
          this.rBaixaImunidade='Baixa Imunidade',
          this.rBurnout='Burnout',
          this.rLaringite='Laringite',
          this.rInsonia='Insônia',
          this.rZumbido='Zumbido',
          this.rLabirintite=`<span><h4>Labirintite</h4></span>
          <br>
          <span class='white'>Labirintite é o nome popular que se dá a todos os transtornos do labirinto, uma estrutura interna do ouvido composta pela cóclea (imprescindível para a 
          nossa audição), pelo vestíbulo e pelos canais semicirculares (que têm papel na manutenção do nosso equilíbrio).</span>`,
          this.rSinusite='Sinusite'
      },
      sinusite() {
          this.aplicarAcu = true,
          this.aplicarCran = true,
          this.aplicarAur = false,
          this.aplicarVen = false,
          this.aplicar = false,
          this.aplicarTwo = false,
          this.aplicarTree = false,
          this.aplicarFour = false,
          this.aplicarFive = false,
          this.aplicarSix = false,
          this.aplicarSeven = false,
          this.aplicarEight = false,
          this.aplicarNine = false,
          this.aplicarTen = false,
          this.aplicarEleven = false,
          this.aplicarTwelve = false,
          this.aplicarThirteen = false,
          this.aplicarFourteen = true,
          this.rAnsiedade = 'ansiedade',
          this.rDepressao = 'Depressão',
          this.rEstresse='Estresse',
          this.rCervicalgia='Cervicalgia',
          this.rLombalgia= 'Lombalgia',
          this.rEnxaqueca= 'Enxaqueca',
          this.rCefaleia='Cefaleia',
          this.rBaixaImunidade='Baixa Imunidade',
          this.rBurnout='Burnout',
          this.rLaringite='Laringite',
          this.rInsonia='Insônia',
          this.rZumbido='Zumbido',
          this.rLabirintite='Labirintite',
          this.rSinusite=`<span><h4>Sinusite</h4></span>
          <br>
          <span class='white'>é a inflamação das mucosas dos seios da face, região do crânio formada por cavidades ósseas ao redor do nariz, maçãs do rosto e olhos. Os 
          seios da face dão ressonância à voz, aquecem o ar inspirado e diminuem o peso do crânio, o que facilita sua sustentação.</span>`
      }
  }
} 
</script>
