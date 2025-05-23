<template>
  <head class="top">
    <h1>GESTION DES VISITEURS</h1>
  </head>
  <nav>
    <router-link to="/">Ajout</router-link> |
    <router-link to="/listage">Liste</router-link> |
    <router-link to="/bilan">Bilan</router-link>
  </nav>
  <router-view/>
</template>

<style>
/* change  */
/* Maer32's change */
@font-face {
  font-family: Font;
  src: url(/src/assets/font/Poppins.ttf);
}

/* fgdg */
* {
  font-family: Font;
  padding: 0;
  margin: 0;
  list-style: none;
  text-decoration: none;
}
 
.top {
  display: block;
}


</style>
