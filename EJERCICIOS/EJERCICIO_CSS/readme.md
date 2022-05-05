5. LENGUAJE CSS
Objetivo: Verificar el dominio de implementación de estilos (CSS) sobre el código html de una página web.

Indicaciones: Pedir subrayar, encerrar en un círculo, o escribir la respuesta que consideren correcta.

Preguntas:

¿Qué significa CSS? (valor 0,25)

     a) Cascading Style Sheets
     
   
¿Cuál es el HTML correcto para hacer referencia a una hoja de estilo externa? (valor 0,25)

     
     b) <link rel="stylesheet" type="text/css" href="style.css">
     
  
¿En qué parte de un documento HTML es el lugar correcto para hacer referencia a una hoja de estilo externa? (valor 0,25)

     a) En la sección <head>
     
  
¿Qué etiqueta HTML se utiliza para definir una hoja de estilo interno? (valor 0,25)

    
    c) <style>
  
¿Qué atributo HTML se usa para definir estilos en línea? (valor 0,25)

   
    b) styles
    
¿Cuál es la sintaxis CSS correcta? (valor 0,25)

    
    b) body {color: black;}
    
  
¿Cómo se inserta un comentario en un archivo CSS? (valor 0,25)

    a) /* esto es un comentario */
   
  
¿Qué propiedad se utiliza para cambiar el color de fondo? (valor 0,25)

     
     b) background-color
     
   
¿Cómo se agrega un color de fondo para todos los elementos h1 (valor 0.25)

    
     b) h1 {background-color:#FFFFFF;}
     
   
¿Qué propiedad CSS se usa para cambiar el color del texto de un elemento? (valor 0,25)

    
    c) color
  
¿Qué propiedad CSS controla el tamaño del texto? (valor 0,25

   
   c) font-size
   
 
¿Cuál es la sintaxis CSS correcta para poner en negrita todos los elementos p?(valor 0.25)

   
   
   c) p {font-weight:bold;}
   
   
¿Cómo hacer que cada palabra en un texto comience con una letra mayúscula? (valor 0,25)

    
    b) text-transform:capitalize
   

¿Qué propiedad se utiliza para cambiar la fuente de un elemento? (valor 0,25)

   
    b) font-family
    
     
¿Cómo pones el texto en negrita? (valor 0,25)

    
    c) font-weight:bold;
     
¿Cómo se muestra un borde como este? (valor 0,25)

El borde superior = 10 píxeles

El borde inferior = 5 píxeles

El borde izquierdo = 20 píxeles

El borde derecho = 1 píxel

        a) border-width:10px 1px 5px 20px;
        (valor 0.25)
     
¿Qué propiedad se usa para cambiar el margen izquierdo de un elemento? (valor 0,25)

   
    b) margin-left
     
Al usar la propiedad de relleno (padding); ¿Está permitido usar valores negativos? (valor 0,25)

      a) No
     
     
¿Cómo se selecciona un elemento con id 'demo'? (valor 0,25)

    
     b) #demo
     
     
20.¿Cómo se seleccionan elementos con el nombre de clase 'test'? (valor 0,25)

          
          b) .test
          
     
¿Cómo se seleccionan todos los elementos p dentro de un elemento div? (valor 0,25)

     
      b) div p
      
     
22.¿Cómo se agrupan los selectores? (valor 0,25)

          
          c) Separe cada selector con una coma
     
¿Cuál es el valor predeterminado de la posición de propiedad? (valor 0,25)

      
      
      d) static
     
24.¿Cómo se hace una lista que enumera sus elementos con cuadrados? (valor 0,25)

          
          c) list-style-type: square;
     
Realice la maquetación del siguiente ejemplo de página: (se aplica la rúbrica de la maquetación en código html y css, valor 36)

imagen
     
   


● Este ejercicio lo deberás realizar con las etiquetas de HTML5, haciendo uso de los elementos semánticos de HTML5.

● deberías, en un bloque de notas, colocar todo el código html5 y guárdalo con extensión .html

● Lo mismo hará con el código CSS3, deberá guardar en un bloque de notas el código css3 con extensión .css.

● Guarde ambos archivos, el código html5 y css3, en una misma carpeta.

● Recuerda usar el elemento link para llamar dentro del código html5 los estilos guardados en el archivo con extensión .css.

-Hay tres imágenes que utilizaron para realizar esta actividad: Imagen del logo institucional. https://escuelasdecodigo.cdmx.gob.mx/wp-content/themes/escuelasdecodigo/assets/images/logo.svg

Imagen del vector blanco que se encuentra antes del texto “Aprende a programar”. https://escuelasdecodigo.cdmx.gob.mx/wp-content/themes/escuelasdecodigo/dist/assets/hero-vector.svg

Imagen paisaje de la Ciudad de México https://escuelasdecodigo.cdmx.gob.mx/wp-content/themes/escuelasdecodigo/dist/assets/hero.jpg

-El texto alternativo para la primera imagen debe ser “Gobierno de la Ciudad de México”

      INGRESA AQUI EL CÓDIGO HTML
           <!doctype html>
     <html>
     <head>
       <title>EDC CDMX></title>
       <link rel="stylesheet" href="css/estilos.css">
       <link rel="preconnect" href="https://fonts.googleapis.com">
       <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
       <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300&display=swap" rel="stylesheet">
      </head>
     <body>
      <header>
       <img src="img/logo.svg" alt="logo"> <hr>


       <nav>
        <ul>
         <li>Residentes </li>
         <li>Negocios </li>
         <li> Visitantes </li>
         <li> Gobierno </li>
        </ul>
       </nav>

      <div id="encabezado" >
         <div class="texto">
         <p><span>></span>APRENDE A PROGRAMAR EN LAS <span>ESCUEALAS DE CÓDIGO </span> DE LA CDMX </p>
         </div>
     </div>

     <h2>¿Quién se puede inscribir? </h2>
     <h3>Cualquier persona que quiera aprender a programar código y cuente con 4-8 horas disponibles a la semana </h3>
     <h4> *Menores de edad deberan entrar a las instalaciones acompañados de un adulto </h4>

     </body>
     </html>
      
      
      
      INGRESA AQUI EL CSS
                * {
          margin 0 ;
          padding 0 ;
          font-family: 'Roboto', sans-serif;
          } 

          ul {
          color: green ;
          display: flex;
          justify-content:flex-end;
          list-style-type: none;

          }

          li{
              margin-right: 20px;
          }


          h2{
              color: goldenrod;
              text-align: center;
          }

          h3, h4 {
              text-align: center;
          }

          #encabezado {
              display: flex;
              align-items: center;
              height: 70vh;
              background: url("../img/hero.jpg");
              background-position: center;
              background-size: cover;

          }

          .texto {
              color: #fff;
              width: 50%;
              font-size: 80px;
              text-align: right;


          }

          span {
              font-weight: bolder;
          }



      
      
      
      
      
      
      
      
      
      
      
      
      
      
           
Ingresa el enlace a tu página del proyecto final

https://maribelzarate.github.io/proyecto-final-/

