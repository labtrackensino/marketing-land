<template>
<div>
  <div class="header">
    <b-container>
      <b-row>
        <b-col class="my-3">
          <b-img right :src="require('@/assets/img/logo.png')" />
        </b-col>
      </b-row>
      <b-row>
        <b-col md="7" class="ml-auto text-right my-5">
          <h1 class="font-weight-bolder">Comece hoje a impulsionar seu <span class="text-danger">negócio em 4 passos</span></h1>
        </b-col>
      </b-row>
      <b-row>
        <b-col md="5" class="ml-auto text-right my-5">
          <h3>Aprenda conceitos de <span class="text-danger">marketing e vendas digitais</span></h3>
        </b-col>
      </b-row>
    </b-container>
  </div>
  <div class="carrousel bg-danger py-3">
    <VueSlickCarousel :autoplaySpeed="5000" :arrows="false" autoplay>
      <b-container fluid>
        <b-row>
          <b-col cols="3" sm="2" class="text-right">
            <h1 class="m-0">31%</h1>
          </b-col>
          <b-col>das empresas mudaram o funcionamento durante a pandemia para se adaptar e manter a saúde financeira.</b-col>
        </b-row>
      </b-container>
      <b-container fluid>
        <b-row>
          <b-col cols="3" sm="2" class="text-right">
            <h1 class="m-0">76%</h1>
          </b-col>
          <b-col>dos micro empreendedores tiveram queda no faturamento em 2020.</b-col>
        </b-row>
      </b-container>
      <b-container fluid>
        <b-row>
          <b-col cols="3" sm="2" class="text-right">
            <h1 class="m-0">47%</h1>
          </b-col>
          <b-col>dos pequenos negócios dizem ainda ter muitas dificuldades para manter o seu negócio.</b-col>
        </b-row>
      </b-container>
      <b-container fluid>
        <b-row>
          <b-col cols="3" sm="2" class="text-right">
            <h1 class="m-0">92%</h1>
          </b-col>
          <b-col>das empresas brasileiras foram forçadas a reinventar seu modelo de negócio por conta da pandemia.</b-col>
        </b-row>
      </b-container>
    </VueSlickCarousel>
  </div>
  <div class="text bg-white text-dark">
    <b-container class="py-5">
      <p><b>2020</b> foi um ano desafiador para todos nós, muitos perderam seus empregos ou tiveram que se virar para manter o seu negócio em pé.</p>
      <p>Com o isolamento social, tivemos que migrar forçadamente para o <b>mundo digital</b>, e até quem não estava acostumado, foi obrigado a se adaptar ao ambiente online.</p>
      <p><b>Vender online</b> então? As redes sociais se tornaram um verdadeiro leilão de ofertas.</p>
      <p>E como é difícil competir nesse mar de tubarões, não é mesmo?! Quem já se dava bem vendendo online encheu o bolso, mas os peixinhos pequenos como nós tivemos que nos "virar nos 30" para manter nosso negócio rodando.</p>
      <p>O que todas essas <b>pessoas</b> que <b>vendem milhões na internet</b> tem em <b>comum?</b> O que elas fazem de diferente?</p>
    </b-container>
  </div>
  <div class="image-left bg-danger">
    <b-container class="p-4">
      <b-row>
        <b-col>
          <h1 class="text-center">Estratégia de <b>marketing digital</b></h1>
          <p class="text-center">Com uma boa estratégia de marketing qualquer um pode:</p>
        </b-col>
      </b-row>
      <b-row>
        <b-col md="4">
          <b-img fluid :src="require('@/assets/img/im01.png')" />
        </b-col>
        <b-col>
          <ul class="seta mt-5">
            <li><span>Adquirir <b>novos clientes</b></span></li>
            <li><span>Desenvolver a <b>sua marca</b></span></li>
            <li><span>Se conectar com o <b>público-alvo</b></span></li>
            <li><span>Aumentar seu <b>faturamento</b></span></li>
          </ul>
        </b-col>
      </b-row>
    </b-container>
  </div>
  <div class="text bg-white text-dark">
    <b-container class="py-5">
      <p>Mas sabia que não precisa ser tão difícil assim? Sabia que com um pouquinho de conhecimento e prática, <b>sem gastar nada</b>, você pode <b>lucrar muito online</b>?</p>
      <p>E o melhor, sabia que eu posso te ajudar com isso de uma maneira super simples?</p>
      <p>Se você quer bater um papo comigo, descobrir maneiras de alavancar o seu negócio e marcar presença no mundo digital, vem comigo para o evento <b>Impulsione seu negócio em 4 passos</b>, <a class="text-danger" href="#inscricao">inscreva-se aqui!</a></p>
      <p>Mas aproveitando que está aqui, quero te conhecer melhor. Vai, me conta...</p>
      <b-embed type="iframe" :aspect="aspect" src="https://www.lp.labtrack.com.br/teste/embed/q/67"></b-embed>
    </b-container>
  </div>
  <div class="image-right bg-white text-dark">
    <b-container class="text-justify px-5">
      <b-row>
        <b-col>
          <p>Se aplicar todas essas dicas, tenho certeza que elas vão ajudar o seu negócio a decolar!</p>
          <p>Não sabe do que eu tô falando? Volta ali no questionário, você só precisa responder algumas perguntinhas rápidas, e no final vai receber várias dicas personalizadas com o resultado do seu diagnóstico.</p>
        </b-col>
        <b-col class="text-center" md="4">
          <b-img :src="require('@/assets/img/im02.png')" />
        </b-col>
      </b-row>
    </b-container>
  </div>
  <div class="image-left bg-white text-dark">
    <b-container class="font-italic text-right py-5">
      <b-row>
        <b-col class="text-center" md="4">
          <b-img :src="require('@/assets/img/im03.png')" />
        </b-col>
        <b-col>
          <div class="citacao">
            <p>Mas eu tenho a sensação de que posso te ajudar ainda mais, então quero te fazer um convite!</p>
            <p>Vem conversar comigo ao vivo no evento <b class="text-danger">Impulsione seu negócio em 4 passos</b>, que vai acontecer no dia <b class="text-danger">04/03</b> às <b class="text-danger">20h</b>.</p>
            <p>Nesse dia eu vou falar um pouco sobre as estratégias qeu te falei aqui e vou te mostrar na prática como executar algumas delas, você vai ver o quanto é simples faturar mais online.</p>
          </div>
        </b-col>
      </b-row>
    </b-container>
  </div>
  <div class="bg-danger">
    <b-container class="py-5">
      <h1 class="mb-5">Nesse evento <b>nós vamos conversar</b> sobre:</h1>
      <ul class="seta-circle mx-5">
        <li><span>Elevator Pitch</span></li>
        <li><span>4Ps (praça, produto, preço e promoção)</span></li>
        <li><span>Produto Mínimo Viável (MVP)</span></li>
        <li><span>Análise de precificação</span></li>
        <li><span>Canais e ferramentas digitais</span></li>
        <li><span>Fidelização de clientes</span></li>
        <li><span>Gestão de Relacionamento com o Cliente (CRM)</span></li>
        <li><span>Modelo enxuto</span></li>
        <li><span>Cases</span></li>
        <li><span>Exercícios na prática</span></li>
      </ul>
    </b-container>
  </div>
  <div id="inscricao" class="bg-white text-dark">
    <b-container class="p-5">
      <div>Imperdível né?</div>
      <div>Então, posso contar com sua presença?</div>
      <b-embed type="iframe" :aspect="aspect" src="https://www.lp.labtrack.com.br/teste/embed/q/70"></b-embed>
    </b-container>
  </div>
  <div class="bg-white text-dark image-right">
    <b-container class="sobre p-4">
      <b-row>
        <b-col lg="6">
          <h1 class="my-0">Quem sou eu?</h1>
          <h1 class="text-danger mb-4 font-weight-bold">Vaime Junior</h1>
          <p>Me formei em Técnico em informática pela Satc em 2011, depois me graduei em Administração com ênfase em marketing, publicidade e propagada pela Esucri em 2018.</p>
          <p>Atuo há 10 anos como programador de sites, sistemas e lojas virtuais. Foram lançados até hoje mais de 100 sites, e mais de 15 sistemas criados.</p>
        </b-col>
      </b-row>
      <b-row>
        <b-col md="6">
          <p>Entusiasta no mundo da inovação, me tornei co-fundador da Chawork e sócio da LabTrack.</p>
        </b-col>
      </b-row>
      <b-row>
        <b-col cols="6">
          <p>Trabalhando voluntariamente em ativação de comunidades impactei mais de 2 mil pessoas com todos os eventos organizados, além de mentorar mais de 60 negócios.</p>
        </b-col>
      </b-row>
    </b-container>
  </div>
  <div class="bg-dark">
    <b-container class="py-5">
      <b-row>
        <b-col md="8">
          <p>Ficou com alguma dúvida? Fale com a gente!</p>
          <div>E-mail: comercial@labtrack.com.br</div>
          <div>WhatsApp: (48) 99174-3111</div>
        </b-col>
        <b-col>
          <a href="https://api.whatsapp.com/send?phone=+5548991743111">
            <b-img right :src="require('@/assets/img/whatsapp.png')" />
          </a>
        </b-col>
      </b-row>
    </b-container>
  </div>
</div>
</template>

<script>
import VueSlickCarousel from 'vue-slick-carousel'
import 'vue-slick-carousel/dist/vue-slick-carousel.css'
// optional style for arrows & dots
import 'vue-slick-carousel/dist/vue-slick-carousel-theme.css'

export default {
  name: 'MyComponent',
  components: { VueSlickCarousel },
  data() {
    return {
      aspect: '21by9'
    }
  },
  methods: {
    resize() {
      const windowWidth = window.innerWidth
      if (windowWidth >= 992) {
        this.aspect = '21by9'
      } else if (windowWidth >= 600) {
        this.aspect = '4by3'
      } else {
        this.aspect = '1by1'
      }
    }
  },
  mounted() {
    this.resize()
    window.onresize = () => {
      this.resize()
    }
  }
}
</script>
<style lang="scss">
  $red: #F07341;
  $gray-800: #000;
  @import 'node_modules/bootstrap/scss/bootstrap.scss';
  @import 'node_modules/bootstrap-vue/src/index.scss';
  @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@400;800&display=swap');

  body.labtrack {
    font-family: 'Montserrat', sans-serif;
    background-color: #606062;
    color: #fff;
    font-size: 1.2em;

    .header {
      min-height: 25em;
      background-size: contain;
      background-position: bottom left;
      background-repeat: no-repeat;
      background-image: url('./assets/img/banner2.png');
    }

    .sobre {
      background-color: #ddd ;
      background-image: url('./assets/img/im04.png');
      background-position: bottom right;
      background-size: 40%;
      background-repeat: no-repeat;
      p {
        margin-bottom: 0;
        padding-bottom: 1em;
      }
    }

    .carrousel {
      .slick-slider {
        margin: 0 auto;
        max-width: 40rem;
      }
    }

    ul.seta {
      list-style: none;
      padding-inline-start: 0;
      li {
        span {
          padding-left: 10px;
        }
        padding-bottom: 1.2em;
      }
      li::before {
        content: '';
        height: 1em;
        width: 1em;
        background-image: url('./assets/img/seta.png');
        background-size: contain;
        background-repeat: no-repeat;
        padding-left: 1.5em;
      }
    }

    ul.seta-circle {
      list-style: none;
      padding-inline-start: 0;
      li {
        span {
          margin-left: 0.4em;
        }
      }
      li::before {
        content: '';
        height: 1em;
        width: 1em;
        background-image: url('./assets/img/seta02.png');
        background-size: contain;
        background-repeat: no-repeat;
        padding-left: 1.5em;
      }
    }

    .image-left {
      img {
        margin-right: 60px;
      }
    }

    .citacao {
      p {
        margin-left: 3rem;
        margin-right: 3rem;
      }
      p:first-child::before {
        content: "\"";
        font-size: 3rem;
        float: left;
        margin-top: -2rem;
      }
      p:last-child::after {
        content: "\"";
        font-size: 3rem;
        float: right;
        margin-right: -2rem;
      }
    }

    .image-right {
      padding-top: 1rem;
      padding-bottom: 1rem;
    }
  }
</style>
