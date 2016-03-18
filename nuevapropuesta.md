<html>
<head>
<h1><title>Vendedor</title></h1>
      <link rel="stylesheet" href="https://storage.googleapis.com/code.getmdl.io/1.0.6/material.indigo-pink.min.css">
      <script src="https://storage.googleapis.com/code.getmdl.io/1.0.6/material.min.js"></script>
      <link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons">
    </head>
  <div id="page">
  <div id="header">
  <div id="logo">
	<span class="android-mobile-title mdl-layout-title">
  <img class="android-logo-image" src="g4357.png" style="width:80px;height:50px">
</span>
	</div>
	<td>
      <div class=”mdl-layout mdl-js-layout”>
    <header class=”mdl-layout__header”>
    <div class=”mdl-layout-icon”></div>
                <div class="bar">   
                 <div class=”mdl-layout__header-row”>
            <span class=”mdl-layout__title”><center><h1>Vendedor</h1></center></span>
            <div class="container mdl-shadow--2dp">
            <button id="demo_menu-lower-left" class="mdl-button mdl-js-button mdl-button--icon" data-upgraded=",MaterialButton">
               <i class="material-icons">more_vert</i>
            </button>
            <ul class="mdl-menu mdl-menu--bottom-left mdl-js-menu mdl-js-ripple-effect"   for="demo_menu-lower-left">
               <li class="mdl-menu__item">Vendedor</li>
               <li disable class="mdl-menu__item">Inspector</li>
               <li disable class="mdl-menu__item">Administración</li> 
               <li disable class="mdl-menu__item">Cobrador</li>  
            </ul>        
         </div>
         <div class="background"></div>
      </div>
    </header>
</div>
   </td>
<script src="http://ajax.googleapis.com/ajax/libs/angularjs/1.4.8/angular.min.js"></script>
<body>
<div ng-app="">
<p><h5>Cotizaci&oacute;n</h5></p>
<p>Nombre o Raz&oacute;n Social: <input type="text" ng-model="Nombre o Raz&oacute;n Social"></p>
<p ng-bind="Nombre o Raz&oacute;n Social"></p>
<p>Gestor Inmobiliario o Administrador: <input type="text" ng-model="Gestor Inmobiliario o Administrador"></p>
<p ng-bind="Gestor Inmobiliario o Administrador"></p>

</div>

</body>
</html>
