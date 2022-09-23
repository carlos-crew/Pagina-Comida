<template>
  
  <header>
    <div class="container">
      <div class="row">
        <nav class="menu">

      </nav>
      </div>
    </div>
    <br>
    
  </header>
  <div>
    <div class="container">
      <div class="row">
        <div class="col-md-12 center azul text-white">Ven y Disfruta Los Mejores Platillos En Tu Comidita</div>
      </div>
    </div>
  </div>

  <div class="container center">
    <h1>Tu Comidita</h1>
    <card url="https://www.paulinacocina.net/wp-content/uploads/2020/08/tacos-meat-food-mexican-lunch-dinner-640x480.jpg" nombre="Tacos de Pastor" descripcion="Ya incluye agua de sabor" costo="32"/>
    <card url="https://vivirmejor.mx/wp-content/uploads/2020/08/Comida-Tipica-Mexicana-Pozole-Portada-1200x900.jpg" nombre="Tesmole de Panza" descripcion="Ya incluye agua de sabor" costo="120"/>
    <card url="https://playersoflife.com/wp-content/uploads/2021/09/comida-mexicana-en-guadalajara-portada.jpg" nombre="Tacos de Pollo" descripcion="Ya incluye agua de sabor" costo="22"/>
  
  <card url="https://cdn-3.expansion.mx/dims4/default/2645705/2147483647/strip/true/crop/630x500+0+0/resize/1200x952!/format/webp/quality/90/?url=https%3A%2F%2Fcherry-brightspot.s3.amazonaws.com%2Fgex.lifeandstyle%2Fuploads%2Fasset%2Fasset_file%2F11038%2Fsandiwch-carru.jpg" nombre="Shawish " descripcion="Ya incluye agua de sabor" costo="15"/>
  <card url="https://static.abc.es/media/familia/2018/05/23/Minevera_Pasta-k4KC--1240x698@abc.jpg" nombre="Espagueti con Albondigas" descripcion="Ya incluye agua de sabor" costo="130"/>
  <card url="https://imagenescityexpress.scdn6.secure.raxcdn.com/sites/default/files/2019-05/tehuacan-puebla-donde-comer.jpg" nombre="Chalupas" descripcion="Ya incluye agua de sabor" costo="25"/>

  <card url="http://www.restaurantetehuacan.com/wp-content/uploads/2015/12/chiles-en-nogada.jpg" nombre="Chile Relleno" descripcion="Ya incluye agua de sabor" costo="150"/>
  <card url="https://www.hotelramadaveracruz.com/blog-img/77/7753/8608.jpg" nombre="Mojarra" descripcion="Ya incluye agua de sabor" costo="135"/>
  <card url="https://media-cdn.tripadvisor.com/media/photo-s/1a/e0/1d/42/photo0jpg.jpg" nombre="Milanesas" descripcion="Ya incluye agua de sabor" costo="120"/>
  <card url="https://www.unileverfoodsolutions.com.mx/tendencias/de-mexico-para-el-mundo/platillos-mexicanos/top10-platillos/jcr:content/parsys/content-aside-footer/columncontrol/columnctrl_parsys_1/textimage/image.transform/jpeg-optimized/image.1592429873377.jpg" nombre="Mole" descripcion="Ya incluye agua de sabor" costo="130"/>

  
  </div>

<footer class="text-white">
    <div class="container">
      
    </div>
</footer>
</template>


<script>
  import Card from "./components/Card.vue";
  export default{
    components: { Card},
    
  };
</script>


<style scoped>
footer{
  background-color: #0630b9;
}
h1 {
  text-align: center;
}

.center{
  align-content: center;
  text-align: center;
  align-items: center;
}
.der{
  text-align: left;
}
.gris{
  background-color: #E8EAE9;
}
.azul{
  background-color: red;
  outline: none;
  border: 1px solid red;
  padding: 1.5%;
	width: 100%;
}

.menu a {
  display: block;
  padding: 0.5em;
  background-color: #06B95D;
  text-decoration: none;
  color: #191C26;

  }

.menu a:hover {

  background-color: #191C26;
  }

.menu ul li ul {
  display: none;
  }

.menu ul li a:hover + ul, .menu ul li ul:hover {
  display: block;
  }

</style>