<template>
<div>
  <NavTopTwo/>
  <NavBottom/>

  <div class='main-tree anima'>
      <div>
        <h5><i class="fa-solid fa-blog"></i> Blog <br><br> TCC e Artigos</h5>
      </div>
    </div>

      
        <div class='years'>
            <h4 @click='postOne' class='postTitle' :class='{anima: aplicar, postTitleHover: aplicar }'>
              <i class="fas fa-chevron-right"></i> A Acupuntura no Tratamento da Lombalgia Tai Yang: Revisão Bibliográfica
            </h4>
            <div v-html='outputPostOne'></div>
        
            <br>
            <h4 @click='postTwo' class='postTitle' :class='{ postTitleHover: aplicarTwo }'>
              <i class="fas fa-chevron-right"></i> Auriculoterapia: Uma Visão Geral dentro do Pensamento Oriental e Ocidental. 
            </h4>
            <div v-html='outputPostTwo'></div>
        <!--    <h4 @click='umSete' class='postTitle' :class='{ postTitleHover: aplicarTree }'>| 2017 |</h4>
            <h4 @click='umUm' class='postTitle' :class='{ postTitleHover: aplicarFour }'>| 2011 |</h4>
            <h4 @click='zeroOito' class='postTitle' :class='{ postTitleHover: aplicarFive }'>| 2008 |</h4>
            <h4 @click='zeroCinco' class='postTitle' :class='{ postTitleHover: aplicarSix }'>| 2005 |</h4>
            <h4 @click='oitoSeis' class='postTitle' :class='{ postTitleHover: aplicarSeven }'>| 1986 |</h4>
        -->    
        </div>
        <br>
        <br>

        <!-- <div>
          <span class="nav-in dois-vinte-um">2021</span> | <span class="nav-in dois-vinte">2022</span>
        </div> -->
    </div>
</template>

<script>
export default {
  head: {
    title: 'Blog | Deep Acupuntura',
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
          aplicar : true,
          aplicarTwo : '',
          aplicarTree : '',
          aplicarFour : '',
          aplicarFive : '',
          aplicarSix : '',
          aplicarSeven : '',
          outputPostTwo: '',
          outputPostOne: `
          <p class='post'>
            A Medicina Tradicional Chinesa (MTC) tem sua origem das combinações da prática da moxabustão, acupuntura e 
            da farmacologia natural cujos efeitos e resultados eram eficazes e precisos. A Acupuntura é o conjunto de 
            conhecimentos teórico-empíricos da MTC através da aplicação de agulhas e de moxas. Existem diversas teorias 
            na MTC para podermos...

            <a class='' href='/blog/lombalgia-tai-yang'> Veja mais</a>
            
          </p>
          <br>
          
          
          
          `,
      }
  },
  methods: {
      postOne() {
          this.aplicar = true,
          this.aplicarTwo = false,
          this.aplicarTree = false,
          this.aplicarFour = false,
          this.aplicarFive = false,
          this.aplicarSix = false,
          this.aplicarSeven = false,
          this.outputPostTwo = ``,
          this.outputPostOne = `
          <p class='post'>
            A Medicina Tradicional Chinesa (MTC) tem sua origem das combinações da prática da moxabustão, acupuntura e 
            da farmacologia natural cujos efeitos e resultados eram eficazes e precisos. A Acupuntura é o conjunto de 
            conhecimentos teórico-empíricos da MTC através da aplicação de agulhas e de moxas. Existem diversas teorias 
            na MTC para podermos...

            <a href='/blog/lombalgia-tai-yang'> Veja mais</a>
            
          </p>
          <br>
          `

      },
      postTwo(){
        this.aplicar = false,
          this.aplicarTwo = true,
          this.aplicarTree = false,
          this.aplicarFour = false,
          this.aplicarFive = false,
          this.aplicarSix = false,
          this.aplicarSeven = false,
          this.outputPostOne = ``,
          this.outputPostTwo = `
          <p class='post'>
            Segundo Oleson (2003) a auriculoterapia é uma modalidade
            de saúde em que a superfície externa da orelha, ou aurícula, é
            estimulada para aliviar condições patológicas em outras partes
            do corpo, isso embora, originalmente baseado sobre a antiga
            prática chinesa de acupuntura, a correspondência somatotópica
            de partes do corpo a partes específicas da orelha foi desenvolvido pela...

            <a href='/blog/auriculoterapia-visao-oriental-ocidental'> Veja mais</a>
            
          </p>
          <br>
          `
      },
      umSete() {
        this.aplicar = false,
          this.aplicarTwo = false,
          this.aplicarTree = true,
          this.aplicarFour = false,
          this.aplicarFive = false,
          this.aplicarSix = false,
          this.aplicarSeven = false,
          this.outputPostOne = 
          `
          <p>

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
          this.outputPostOne =
          `
          <h4>2011:</h4>
        <h4 style="text-align: left;">Novembro</h4>
          <ul class="main-l">
            <li>
              Término do curso de Formação de Instrutor de Krav-Maga - Bukan School of Krav-maga - Rio de Janeiro - RJ;
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
          this.outputPostOne =
          `
          <h4>2008:</h4>
        <h4 style="text-align: left;">Fevereiro</h4>
          <ul class="main-l">
            <li>
              Término do curso de Graduação em Educação Física - Universidade Salgado de Oliveita - UNIVERSO;
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
          this.outputPostOne =
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
          this.outputPostOne = 
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
<style>
.years {
    display: flex;
    flex-flow: column wrap;
    align-items: normal;
    justify-content:space-end;  
    align-self: center;
    margin: 0 10px 0 10px;
    font-size: .8em;
}

.years a{
  cursor: pointer;
}
.years h4 {
    font-size: 1.1em;
  cursor: pointer;
}

@media only screen and (min-width: 970px) {
}

.years div h4 {
    font-size: 1.1em;
  cursor: pointer;
}

.post {
  color: #fff;
}

.post a{
  color: #e23a28;
}

.postTitle {
  color: #d8d8d880;
}

.postTitle:hover {
  color: e23a28;
  text-decoration: underline;
}

.postTitleHover {
  color: #e23a28;

}
.postTitleHover:hover {
  text-decoration: none;

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
.main-tree p {
  font-size: .8em;
  color: #fff;
  margin: 0px 0px 15px 30px;
}

.main-tree p i {
  font-size: .8em;
}

.main-tree h5 {
  margin: 10px 0px 15px 10px;
}
</style>
