# desafio-11-matias-igenes
SASS II + SEO

Arregle unotacion de favicon
<!-- Favicon -->

Agregue keywords
<!-- Keywords -->
    <meta name="Keywords" content="Obras Viales, uruguay, artigas, paysandu, ingeniero, civil, HTML, CSS, JS">
    <meta name="description" content="Matias Igenes diseñador de producto, mira mi portofolio">

Agregue maps y map-get

$redes: ( /*Declaramos nuestro mapa*/
        twitter: #55acee,
        facebook:  #3a5795,
        send-mail: #C25E30
); 

/*bucle para usar los valores del mapa*/
@each $red, $color in $redes {
   .btn--#{$red} {
       background-color: $color;
   }
}

/* map-get */ 
$estilos: (
  color: #3673D9,
  centro: center,
  tFuente: 15px,
  1rem : 0.5rem
);

div {
  background-color: map-get($estilos, color);
  text-align: map-get($estilos, centro);
  padding: map-get($estilos, 1rem);
  font-size:map-get($estilos, tFuente);
}

Edite las keywords me quede con 5
<meta name="Keywords" content="Obras Viales, uruguay, artigas, paysandu, ingeniero">

Agregue mixin en sass y css

