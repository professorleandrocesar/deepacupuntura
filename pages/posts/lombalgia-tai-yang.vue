<template>
<div id='app'>

  <NavTopTwo/>
  <NavBottom/>

      <div id="main">
        <div class='years'>
            <a @click="$router.go(-1)"><i class="fas fasi-post main-l fa-arrow-left"></i> Voltar</a>
        </div>  
        <div class="main-c"><i class="fas fasi fa-file-invoice"></i></div>
          <h2>  
              A Acupuntura no Tratamento da Lombalgia Tai Yang:<br> Revisão Bibliográfica¹
          </h2>
          <p class='main-r autors'> 
            FIORI, Lucas²
            <br>
            PAIXÃO, Natália²
            <br>
            GUIMARÃES, Carla²
            <br>
            DA COSTA, Leandro²
            <br>
            MACHADO, Patrique²
            <br>
            De Moraes, Cláudio³

          </p>
        <div class='years'>
            <h4 @click='articleResume' class='postTitle' :class='{ postTitleHover: aplicar }'>
            Resumo Completo
            </h4>
            <a href="/lombalgia-tai-yang.pdf" download="" >
              Download
            </a>
            <div v-html='outputPostOne'></div>
            <div v-html='outputPostTwo'></div>
        <!--    <h4 @click='umSete' class='postTitle' :class='{ postTitleHover: aplicarTree }'>| 2017 |</h4>
            <h4 @click='umUm' class='postTitle' :class='{ postTitleHover: aplicarFour }'>| 2011 |</h4>
            <h4 @click='zeroOito' class='postTitle' :class='{ postTitleHover: aplicarFive }'>| 2008 |</h4>
            <h4 @click='zeroCinco' class='postTitle' :class='{ postTitleHover: aplicarSix }'>| 2005 |</h4>
            <h4 @click='oitoSeis' class='postTitle' :class='{ postTitleHover: aplicarSeven }'>| 1986 |</h4>
        -->    
        </div>
        <br>
      </div>

        <!-- <div>
          <span class="nav-in dois-vinte-um">2021</span> | <span class="nav-in dois-vinte">2022</span>
        </div> -->
    </div>
</template>

<script>
export default {
  head: {
    title: 'A Acupuntura no Tratamento da Lombalgia Tai Yang: Revisão Bibliográfica | Posts | Deep Acupuntura',
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
          outputPostOne: `
          <p class='post'>
            A Medicina Tradicional Chinesa (MTC) tem sua origem das combinações da prática da moxabustão, acupuntura e 
            da farmacologia natural cujos efeitos e resultados eram eficazes e precisos. A Acupuntura é o conjunto de 
            conhecimentos teórico-empíricos da MTC através da aplicação de agulhas e de moxas. Existem diversas teorias 
            na MTC para podermos tratar patologias, como a teoria dos 5 Elementos, Princípio de Geração (Ciclo Sheng), 
            Princípio de Controle (Dominância – Ciclo KE), a teoria Yin/Yang, teoria dos meridianos (canais de energia) e a 
            teoria dos canais unitários. A dor lombar é o principal problema de saúde entre os países ocidentais 
            industrializados e uma das principais causas de despesas médicas, ausência e incapacidade. Existem 4 métodos 
            diagnósticos na MTC que são a inspeção, audição e olfação, anamnese e palpação de pulso e palpação. A lombalgia 
            TaiYang precisa ser diferenciada da lombalgia da protusão e hérnia discais lombar, esta apresenta perda de força 
            muscular, alteração da sensibilidade, hipotrofia dos músculos da perna e sinal positivo no Teste de Lasègue. 
            Pela literatura relacionada à lombalgia Tai Yang, houve evidência consistente da relevância do tratamento da 
            acupuntura para tal patologia, porém é sugestivo estudos mais aprofundados sobre o tema. Objetivos: identificar 
            e diferenciar os diversos tipos de lombalgias dentro da visão ocidental e oriental e assim elaborar o tratamento 
            ideal para os pacientes diagnosticados com Lombalgia TaiYang.
          </p>
          <br>
          <p class='main-l autors'> 
             ¹ TCC do Curso de Pós-graduação em Acupuntura do Centro Universitário Celso Lisboa ² FIORI; PAIXÃO; GUIMARÃES; DA COSTA; MACHADO, pós-graduandos do Curso de Acupuntura do Centro Universitário 
             Celso Lisboa; ³ DE MORAES, Cláudio, professor e orientador. 
          </p>
          <br>
          <br>
          
          
          
          `,
      }
  },
  methods: {
      articleResume() {
          this.aplicar = true,
          this.aplicarTwo = false,
          this.aplicarTree = false,
          this.aplicarFour = false,
          this.aplicarFive = false,
          this.aplicarSix = false,
          this.aplicarSeven = false,
          this.outputPostOne = `
          <p class='post'>
            A Medicina Tradicional Chinesa (MTC) tem sua origem das combinações da prática da moxabustão, acupuntura e 
            da farmacologia natural cujos efeitos e resultados eram eficazes e precisos. A Acupuntura é o conjunto de 
            conhecimentos teórico-empíricos da MTC através da aplicação de agulhas e de moxas. Existem diversas teorias 
            na MTC para podermos tratar patologias, como a teoria dos 5 Elementos, Princípio de Geração (Ciclo Sheng), 
            Princípio de Controle (Dominância – Ciclo KE), a teoria Yin/Yang, teoria dos meridianos (canais de energia) e a 
            teoria dos canais unitários. A dor lombar é o principal problema de saúde entre os países ocidentais 
            industrializados e uma das principais causas de despesas médicas, ausência e incapacidade. Existem 4 métodos 
            diagnósticos na MTC que são a inspeção, audição e olfação, anamnese e palpação de pulso e palpação. A lombalgia 
            TaiYang precisa ser diferenciada da lombalgia da protusão e hérnia discais lombar, esta apresenta perda de força 
            muscular, alteração da sensibilidade, hipotrofia dos músculos da perna e sinal positivo no Teste de Lasègue. 
            Pela literatura relacionada à lombalgia Tai Yang, houve evidência consistente da relevância do tratamento da 
            acupuntura para tal patologia, porém é sugestivo estudos mais aprofundados sobre o tema. Objetivos: identificar 
            e diferenciar os diversos tipos de lombalgias dentro da visão ocidental e oriental e assim elaborar o tratamento 
            ideal para os pacientes diagnosticados com Lombalgia TaiYang.
          </p>
          <br>
          <p class='main-j autors'> 
             ¹ TCC do Curso de Pós-graduação em Acupuntura do Centro Universitário Celso Lisboa ² FIORI; PAIXÃO; GUIMARÃES; DA COSTA; MACHADO, pós-graduandos do Curso de Acupuntura do Centro Universitário 
             Celso Lisboa; ³ DE MORAES, Cláudio, professor e orientador. 
          </p>
          <br>
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
          this.outputPostOne = `
          <p class='post'>
            Breve Histórico da Medicina Tradicional Chinesa (MTC)
Essa ciência é originada da China na Idade da Pedra, isto é, cerca de 2.500 a.C., e apesar de sua antiguidade, continua evoluindo (WEN, 2014, p.7). A Medicina Tradicional Chinesa (MTC) tem sua origem das combinações da prática da moxabustão, acupuntura e da farmacologia natural cujos efeitos e resultados eram eficazes e precisos (NAKANO & YAMAMURA, 2008, p. 17). A MTC é baseada na observação dos fenômenos da natureza e nos estudos e compreensão dos princípios que regem a harmonia nela existente (YAMAMURA, 2004, p. XLIII).
Wen (1995, p.8) cita algumas passagens históricas para a MTC, como a escrita dos livros Era do Imperador Amarelo (2704 – 2100 a.C.), que mostra a Acupuntura com suas bases e um certo nível de desenvolvimento; o livro Hwang Ti Nei Jing (aproximadamente 700 anos a.C.) mostra como os chineses da Idade da Pedra já utilizavam a moxabustão (areia ou pedras quentes) e Acupuntura (agulhas de pedra) para o tratamento de dores abdominais e articulares; e a difusão dos conhecimentos da Acupuntura durante as Dinastias Tsin e Tang (265 – 959 d.C.).
A Acupuntura é o conjunto de conhecimentos teórico-empíricos da MTC através da aplicação de agulhas e de moxas (WEN, 2014, p.9). Para Yamamura (2004, p. LVI), a acupuntura foi idealizada dentro do contexto do Tao e das concepções filosóficas e fisiológicas que nortearam a MTC e, também, a concepção dos Canais de Energia e dos pontos de acupuntura, o diagnóstico energético e o tratamento baseiam-se nas Teorias do Yang e do Yin, dos Cinco Movimentos, da Energia (Qi) e do Xue (Sangue).

Teorias da Medicina Tradicional Chinesa

Teoria dos Cinco Elementos
Há mais de 2.000 anos foram estruturadas as bases da Acupuntura Constitucional dos Cinco Elementos, sendo seus valores e crenças motivos para moldar a prática do sistema de medicina até os dias atuais (HICKS, HICKS & MOLE, 2007, p.1). Segundo Wen (1995, p. 19), os cinco elementos são, na realidade, os cinco elementos básicos que constituem a natureza (Madeira, Fogo, Terra, Água e Metal) e existem entre eles uma interdependência e uma inter-restrição que irão determinar seus de mutação e movimento constantemente.
Para Nakano & Yamamura (2008, p. 21), constitui um dos pilares da Filosofia e da Medicina Tradicional Chinesa e sua concepção baseia-se na evolução dos fenômenos da natureza, em como os vários aspectos que compõem a Natureza geram e dominam uns aos outros. Yamamura (2004, p. XLVI) explica que todos esses fenômenos naturais têm características próprias e podem originar outros fenômenos e ao mesmo tempo sofrer destes influências benéficas ou maléficas. Vale ressaltar a passagem do livro “Princípios de Medicina Interna do Imperador Amarelo”:

O Imperador Amarelo perguntou: "Os cinco elementos da natureza se associam às cinco orientações, do leste, do oeste, do sul, do norte e da parte central para produzir os climas frio, quente, a umidade, a secura e o vento. As cinco vísceras do homem ativam a energia vital para produzir as cinco emoções da alegria desmedida, da raiva, da melancolia, da ansiedade e do terror (BING, 2001, p.322).

Segundo Yamamura (2004, p. XLVI), o Movimento Água é caracterizado pelos fenômenos naturais que indicam retração, profundidade, frio, declínio, queda, eliminação, ponto de partida e chegada da Transmutação dos Movimentos; o Movimento Madeira representa o aspecto de crescimento, movimento, florescimento e síntese; o Movimento Fogo é caracterizado por todos os fenômenos naturais que indicam desenvolvimento, ascensão, atividade e expansão; o Movimento Terra representa fenômenos naturais que se traduzem por mudanças e transformações; e por fim, o Movimento Metal é caracterizado pelos processos naturais de purificação, seleção, análise e de limpeza.
Os conceitos de Yin/Yang e os Cinco Elementos são fundamentados em uma compreensão e exploração dessas relações, sendo essa ênfase importante no significado de equilíbrio e harmonia entre os Cinco Elementos (HICKS, HICKS & MOLE, 2007, p. 8).

Princípio de Geração/Ciclo Sheng
Para Yamamura (2004, p. XLVII), este princípio estabelece que cada Movimento gera o Movimento posterior, também conhecido como regra “mãe-filho”, sendo a “mãe” o Movimento que gera (o Movimento em questão) e “filho” o Movimento seguinte (o Movimento gerado).	O Elemento Água cria a Madeira pela nutrição. Madeira cria Fogo pela queima. Já o Fogo cria Terra pelas cinzas. Da Terra surge o Metal (sinônimo de Rocha/algo encontrado na Terra) pelo endurecimento. E por fim, do Metal surge a Água pelo resfriamento (HICKS, HICKS & MOLE, 2007, p.9).

FIGURA 1 – Ciclo Sheng (HICKS, HICKS & MOLE, 2007, p.8).

Princípio de Controle (Dominância) /Ciclo Ke
Este princípio explica que cada Movimento apresenta dominância sobre o Movimento que sucede, isto é, aquele que gerou, também conhecido como regra “avô-neto” e tem como finalidade controlar o crescimento descontrolado que ocorreria se houvesse somente o ciclo de geração, é chamado de “avô” o Movimento que domina e “neto” o Movimento dominado (YAMAMURA, 2004, p. XLVII). Este ciclo pode ser descrito da seguinte maneira: Fogo controla Metal, derretendo-o; Já o Metal controla Madeira, cortando-a; a Madeira controla a Terra, cobrindo-a; Terra controla Água, represando-a; finalizando, a Água controla o Fogo, extinguindo-o (HICKS, HICKS & MOLE, 2007, p. 9-10).

Figura 2 – Ciclo Ke (HICKS, HICKS & MOLE, 2007, p.10).

Teoria Yin/Yang
O conceito de Yin e Yang é a base da MTC, sendo um pensamento chinês como fenômeno de dois extremos de algo contínuo e é uma tendência na visão ocidental de analisar essa teoria como os opostos absolutos (ROSS, 1994, p. 5). Segundo Wen (2014, p. 20), na China antiga, observou-se que a estrutura básica do ser humano era a mesma do universo, então todos os fenômenos da natureza foram classificados em dois polos opostos: Yin (negativo – frio, fraqueza, escuridão, profundo, etc.) e Yang (positivo – calor, força, claridade, superfície, grandeza etc.).
O Yang só pode existir na presença do Yin, e vice-versa, e justamente por essa dualidade é que dá origem a tudo na Natureza, incluindo a vida (NAKANO & YAMAMURA, 2008, p.20). Para Wen (2014, p.22), numa relação de influência e transformação, dentro de uma substância, os elementos Yang e Yin não são fixos, mas estão em constante transformação, e se gerar perda ou ganho de um elemento, terá uma repercussão complementar e direta no outro.

Teoria dos Meridianos (canais de energia)
Nos dias atuais, desconhece-se a origem da criação dessa teoria, sendo muito provável que a Acupuntura e as Qi-Kung (artes marciais) tenham sua contribuição para a sua formação (WEN, 2014, p.28). Os canais de energia constituem a ligação entre o meio interno e meio externo, transmitindo as várias formas de energia entre esses dois meios (YAMAMURA, 2004, p.1).
Os principais meridianos são 12, bilaterais, apresentando-os ambos os cursos, um profundo e outro superficial, tendo como função a distribuição do Qi visceral para todos os tecidos do corpo humano (SOLINAS, MAINVILLE & AUTEROCHE, 2000, p. 26). Os Jing Luo (meridianos) são locais privilegiados que ligam os órgãos e os membros, fazem comunicação entre o baixo e o alto, interior e superfície, regulando o funcionamento de cada parte do corpo onde circulam o sangue e o Qi (AUTEROCHE & NAVAILH, 1992, p.49).
Ainda de acordo com Auteroche & Navailh (1992, p.49-50), em se tratando da natureza da energia, os meridianos são divididos em 6 Yin e 6 Yang, sendo os 6 Yin pertencentes aos órgãos Zang (Coração, Pericárdio, Pulmão, Fígado, Baço-Pâncreas e Rim) e os 6 meridianos Yang são pertencentes aos órgãos Fu (Triplo Aquecedor, Estômago, Intestino Grosso, Intestino Delgado, Bexiga e Vesícula Biliar).

Canais de Energia Unitários
Para Yamamura (2004, p. 722), os Canais de Energia Unitários são formados por um canal de energia principal da mão e um canal de energia principal do pé que apresentam funcionalidades energéticas iguais, possuindo 3 Canais  Unitários Yang e 3 Canais Unitários Yin, podendo assim ser constituídos:
Tai Yang: mais superficial, constituído por dois canais de energia Principal, um que representa o Alto, situado no membro superior (Intestino Delgado), e outro que representa o Baixo, dirigindo-se da face para o membro inferior (Bexiga);
Shao Yang: localizada na camada de energética intermediária, constituído pelos canais Tripo Aquecedor (Alto, mão) e Vesícula Biliar (Baixo, pé);
Yang Ming: o mais profundo dos Canais Unitários Yang, promovendo a comunicação do Exterior (Yang) com o Interior (Yin) e é formado pelo Intestino Grosso (Alto, mão) e Estômago (Baixo, pé);
Tai Yin: mais superficial, formado pelo Pulmão (mão) e Baço-Pâncreas (pé) e este canal se comunica com o Yang Ming;
Jue Yin: localizado na camada energética intermediária, formado pelo canais Circulação-Sexualidade (mão) e Fígado (pé);
Shao Yin: o mais profundo dos Canais Unitários Yin, constituído pelo Coração (mão) e Rim (pé). 
A técnica dos Canais Unitários liga dois meridianos da mesma polaridade, formando só uma unidade energética e conectando o alto e o baixo, como também no sentido contrário, através da ação dos pontos Shu Antigos e assim, os objetivos dessa técnica são o equilíbrio energético e a harmonização dos canais (GARDIN & FELIPE, 2013, p.291).


Figura 3 – Fluxos e conexões dos Meridianos (WEN, 2014, p. 33).

          </p>
          <br>
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
    flex-flow: row wrap;
    align-items: center;
    justify-content:space-end;  
    align-self: center;
}
.years h4 {
  padding: 5px 10px;
  cursor: pointer;
}

.postTitle {
  color: #d8d8d880;
}

.postTitleHover {
  color: #e23a28;
}

.years a {
   color: #d8d8d880;
 }

@media only screen and (max-width: 820px) {
 .years h4, .years a{
   font-size: 1.2em;
 }
}

</style>
