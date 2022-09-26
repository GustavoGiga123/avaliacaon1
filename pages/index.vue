<template>
  
  <section>
    <h1 class="title"><strong>Uma ampla gama de cursos para você!</strong></h1>
    <h1 class= "subtitle">Mais de 1 milhão de cursos sobre como vender cursos, professores nativos, pack do pezinho e muito mais</h1>

    <div>

    <section>
      <b-tabs>
        <b-tab-item label="Trava Zap"> 
            <h1 class="subtitle is-5"><strong>Amplie suas oportunidades de carreira com aulas de golpe do Zap</strong></h1>
        Se você trabalha com mercenários ou tias da cantina ou está buscando uma carreira como mecânico da Carfix, o trava Zaps é umas das habilidades mais importantes que você pode aprender! A sintaxe simples do Zap é especialmente adequada para apps de Desktop, web e negócios.
        </b-tab-item>

        <b-tab-item label="Python">
          Lorem <br />
          ipsum <br />
          dolor <br />
          sit <br />
          amet.
        </b-tab-item>
      </b-tabs>
    </section>

  </div>
    
    <b-button tag="router-link" :to="{ path: '/sobre' }" type="is-dark ml-3">Descubra outras categorias</b-button>
    
      <section class="section">
  <div class="columns">
  <div class="column">
    <img 
      src="https://static-media.hotmart.com/qH_uTqGXwCQ9qa2-e3NbD4QHJXE=/300x300/smart/filters:format(webp):background_color(white)/hotmart/product_pictures/6a6d27d0-8776-4ab2-ba57-a525ff770f94/dolado.png?w=920"></img>
    <p class="subtitle">Mestres do trava Zap</p>
    R$199,90
    <section>
        <b-rate custom-text=""></b-rate>
        <b-rate 
            icon-pack="fas" 
            @change="success" 
            </b-rate>
    </section>
  </div>
  <div class="column">
    <img 
      src="https://static-media.hotmart.com/5MTGoAQ5S8Tk4eg8L0sqAdAHX0M=/300x300/smart/filters:format(webp):background_color(white)/hotmart/product_pictures/279fdb42-7df2-426b-93b1-ba948e158840/hotmartcapaproduto02PNG.png?w=920">
   <p class="subtitle">Como meditar</p>
    R$599,90
    <section>
        <b-rate custom-text=""></b-rate>
        <b-rate 
            icon-pack="fas" 
            @change="success" 
            </b-rate>
    </section>
  </div>
  <div class="column">
    <img 
      src="https://static-media.hotmart.com/cgz-5S0kkZD4eLEKCoFkVFZWUGQ=/300x300/smart/filters:format(webp):background_color(white)/hotmart/product_contents/4c1b125f-201c-4bb5-9539-063fcea5ef14/Logo7.jpg?w=920">
   <p class="subtitle">Seja um agiota</p>
    R$199,90
    <section>
        <b-rate custom-text=""></b-rate>
        <b-rate 
            icon-pack="fas" 
            @change="success" 
            </b-rate>
    </section>
  </div>
  <div class="column">
    <img 
      src="https://static-media.hotmart.com/4N6F_QovPUw8oDr7CzIFvNuZmUY=/300x300/smart/filters:format(webp):background_color(white)/hotmart/product_pictures/722376df-e637-4643-ad44-75af9a98822a/capa52012.png?w=920">
   <p class="subtitle">Curso de maquiagem</p>
    R$1099,90
    <section>
        <b-rate custom-text=""></b-rate>
        <b-rate 
            icon-pack="fas" 
            @change="success" 
            </b-rate>
    </section>
  </div>
</div>
      </section>
  </section>
  

  
</template>

