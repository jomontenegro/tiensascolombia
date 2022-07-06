<template>
<body>
  <div>
    <b-container fluid>
      <b-row>
        <b-col class="cont">
          <b-img
            fluid
            src="../static/Banner_About.png"
            alt="Acerca de Tiendas Cololombia"
            class="Banner_About"
          >
          </b-img>
        </b-col>
      </b-row>
    </b-container>
    <hr />
    <div class="about-padre">
      <div class="about-hijo">
        <h2>Historia de mi Tesis</h2>
        <p>
          Lorem Ipsum es simplemente el texto de relleno de las imprentas y
          archivos de texto. Lorem Ipsum ha sido el texto de relleno estándar de
          las industrias desde el año 1500, cuando un impresor (N. del T.
          persona que se dedica a la imprenta) desconocido usó una galería de
          textos y los mezcló de tal manera que logró hacer un libro de textos
          especimen. No sólo sobrevivió 500 años, sino que tambien ingresó como
          texto de relleno en documentos electrónicos, quedando esencialmente
          igual al original. Fue popularizado en los 60s con la creación de las
          hojas "Letraset", las cuales contenian pasajes de Lorem Ipsum, y más
          recientemente con software de autoedición, como por ejemplo Aldus
          PageMaker, el cual incluye versiones de Lorem Ipsum.
        </p>
      </div>
      <div class="about-hijo2">
        <div class="about-imagenes">
          <!-- <p>
          Lorem Ipsum es simplemente el texto de relleno de las imprentas y
          archivos de texto. Lorem Ipsum ha sido el texto de relleno estándar de
          las industrias desde el año 1500, cuando un impresor (N. del T.
          persona que se dedica a la imprenta) desconocido usó una galería de
          textos y los mezcló de tal manera que logró hacer un libro de textos
          especimen. No sólo sobrevivió 500 años. 
        </p> -->
          <img
            class="img-about"
            src="../static/Basketball.png"
            alt="basketball.png"
            width="100%"
          />
        </div>
      </div>
    </div>
  </div>
</body>
  
</template>

<style>
.img-about {
  padding-top: 0px;
  width: 50%;
  margin-top: 0px;
}
.about-imagenes {
  background-color: red;
  height: 100%;
  margin-left: 10px;
}
.cont {
  /* background-color: #E9FF6A; */
  width: auto;
  background-color: #939597;
  text-align: center;
  height: 100%;
  font-family: "Franklin Gothic Medium", "Arial Narrow", Arial, sans-serif;
}
h2 {
  text-align: left;
  color: #000000;
  font-family: "Franklin Gothic Medium", "Arial Narrow", Arial, sans-serif;
}
h1 {
  padding-left: 1rem;
  text-align: left;
  color: #f5df4d;
}
.Banner_About {
  width: 80%;
}
.about-hijo {
  height: 100%;
  width: 45%;
  display: inline-block;
  padding: 4rem 8rem;
}
.about-hijo2 {
  height: 100%;
  width: 38%;
  display: inline-block;
}
.about-padre {
  height: 100%;
  padding: 1rem;
  width: auto;
  background-color: #ffcc33;
  display: inline-block;
}
@media screen and (max-width: 768px) {
  .about-padre {
    height: 100%;
    /* padding: 1rem; */
    width: 100%;
    background-color: #ffcc33;
    display: inline-block;
    padding: 1rem;
  }
  .about-hijo {
    height: 100%;
    width: auto;
  }
}
p {
  display: inline-block;
  text-align: justify;
}
hr {
  height: 2px;
  background-color: #000;
  margin: 0%;
}

/* estilos de grilla */
* {
  margin: 0;
  padding: 0;
}
body {
  background: #ffcc33;
  color: #000;
  font-family: "Franklin Gothic Medium", "Arial Narrow", Arial, sans-serif;
}
/* creando las grillas que estan dentro de la clase grid */
.grid div {
  background: #ecf0f1;
  padding: 1rem;
}
.grid div:hover {
  border: 1px solid red;
}
.grid {
  display: grid;
  grid-template-columns:repeat(4, 1fr);
  gap: 1em;
  grid-template-rows: minmax(100px, auto);
 /* grid-template-columns: 200px 200px 400px;
  grid-template-rows: auto 400px;
  gap: 1em;
   column-gap: 1em; */
}
/* ---------------------------------------------------------------- */

</style>