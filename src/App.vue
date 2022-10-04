<template>
  <h1 slot="name">COMIDA RAPIDA DOÑA JUANA</h1>
  <br>
  <nav>
  <ul class="list">
    <li slot="categoria">PIZZA</li>
    <li slot="categoria">HAMBUERGUESAS</li>
    <li slot="categoria">REFRESCOS</li>
  
  </ul>
  </nav>
   
  <div class="card-principal">
    <div class="card_landig">
      <p class="title">PIZZA</p>
      <img src="https://www.pizzaycome.com/wp-content/uploads/2021/12/PYC_CLASICA.png" alt="">
    </div>
    <div class="card-info">
    </div>
  
    <div class="contenet">
      <p class="titulo">Pizza Pepperoni</p>
      <p class="precio">$120</p>
      <button type="button">Comprar</button>
      
    </div>
  
  </div>
  <div class="card-principal">
    <div class="card_landig">
      <p class="title">PIZZA</p>
      <img src="https://www.cardamomo.news/__export/1644422142162/sites/debate/img/2022/02/09/pizza_hawaiana_crop1644421835991.jpeg_1902800913.jpeg" alt="">
    </div>
    <div class="card-info">
    </div>
  
    <div class="contenet">
      <p class="titulo">Pizza Hawaiana</p>
      <p class="precio">$115</p>
      <button type="button">Comprar</button>
    </div>
  
  </div>
  <div class="card-principal">
    <div class="card_landig">
      <p class="title">HAMBURGUESA</p>
      <img src="https://www.pequerecetas.com/wp-content/uploads/2013/07/hamburguesas-caseras-receta.jpg" alt="">
    </div>
    <div class="card-info">
    </div>
  
    <div class="contenet">
      <p class="titulo">Hamburguesa Clasica</p>
      <p class="precio">$42</p>
      <button type="button">Comprar</button>
    </div>
  
  </div>
  <div class="card-principal">
    <div class="card_landig">
      <p class="title">HAMBURGUESA</p>
      <img src="http://assets.kraftfoods.com/recipe_images/opendeploy/74255_640x428.jpg" alt="">
    </div>
    <div class="card-info">
    </div>
  
    <div class="contenet">
      <p class="titulo">Hamburguesa BBQ</p>
      <p class="precio">$55</p>
      <button type="button">Comprar</button>
    </div>
  
  </div>
  <div class="card-principal">
    <div class="card_landig">
      <p class="title">PAPAS</p>
      <img src="https://www.cardamomo.news/__export/1621290930734/sites/debate/img/2021/05/17/papas_fritas_crop1621290739319.jpeg_242310155.jpeg" alt="">
    </div>
    <div class="card-info">
    </div>
  
    <div class="contenet">
      <p class="titulo">Papas a la francesa</p>
      <p class="precio">$20</p>
      <button type="button">Comprar</button>
    </div>
  
  </div>
  <div class="card-principal">
    <div class="card_landig">
      <p class="title">REFRESCOS</p>
      <img src="https://viprecetas.com/wp-content/uploads/2021/10/cuanto-tiempo-duran-los-refrescos.png" alt="">
    </div>
    <div class="card-info">
    </div>
  
    <div class="contenet">
      <p class="titulo">Bebidas 600ml</p>
      <p class="precio">$25</p>
      <button type="button">Comprar</button>
    </div>
  
  </div>
  </template>
  
  <style>
    img {
      width: 150px;
      height: 100px;
      opacity: 0.5;
      filter: alpha(opacity=50); 
    }
    h1{
    Color: black;
    text-align: center;
      font-family: Helvetica, Geneva, Arial,
            SunSans-Regular, sans-serif 
    } 
    p{
      Color: black;
      text-align: justify;
      font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    }
    li{
      color: black;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }
  </style>
