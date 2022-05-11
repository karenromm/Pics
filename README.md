# Pics

Sitio de imágenes para variedad de usuarios entusiastas de la fotografía


<html><head>
         <script src="https://cdn.jsdelivr.net/npm/vue/dist/vue.js"></script>   
    </head>
 <body>   
  <div id="app1"> 
   

<img v-bind:src="fuenteDeImagen" v-bind:width="tamanoDeImagen" v-on:click.prevent="cambiarImagen">

<br>
<button v-on:click.prevent="meGusta">Me Gusta

    
</button>#likes:{{numLike}}
  </div> 
   
   <script>
  

  </body></html>
