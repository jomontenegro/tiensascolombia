<template>
  <div class="grid">
    <div class="contenedor1">
      <div>
        <b-carousel
          id="carousel-1"
          v-model="slide"
          :interval="4000"
          controls
          indicators
          background="#ababab"
          img-width="1024"
          img-height="480"
          style="text-shadow: 1px 1px 2px #333"
          @sliding-start="onSlideStart"
          @sliding-end="onSlideEnd"
        >
          <b-carousel-slide
            caption="First slide"
            text="Nulla vitae elit libero, a pharetra augue mollis interdum."
            img-src="../static/Banner_About.png"
          ></b-carousel-slide>
        </b-carousel>
      </div>
      <hr />
    </div>
    <div class="contenedor2">
      <h2>Falabella</h2>
      <p class="pcontenedor2">
        Nuestro propósito es simplificar la vida de las personas en América
        Latina, transformando sus experiencias de compra.<br />
        Para esto, estamos impulsando una profunda transformación cultural y una
        nueva manera de trabajar mirando a los próximos años, potenciando
        capacidades que ya son parte de nuestra propuesta de valor e
        incorporando otras nuevas. En este contexto, entendemos la necesidad de
        convertirnos en una organización más ágil y flexible, manteniendo
        nuestra tradición de tener al cliente y a nuestros colaboradores siempre
        al centro de toda nuestra gestión. Esta constante transformación
        cultural que impulsamos está basada en vivir y promover nuestros valores
        y principios corporativos, los cuales son claves para el desarrollo de
        la estrategia de Ecosistema y constituyen el motor de nuestras acciones
        en el día a día.
      </p>
    </div>
    <div class="contenedor3">
      <div class="contenedor3Anidado">
        <div class="span6 left" style="overflow-y: hidden">
          <div class="title">
            <table>
              <tbody>
                <tr>
                  <td>
                    <!-- colocar en la seccion de creditos
                    <a href="https://www.freepik.es/vectores/telefono-contacto">Vector de telefono contacto creado por macrovector_official - www.freepik.es</a> -->
                    <a href="https://github.com/nuxt/nuxt.js" target="_blank"
                      ><svg
                        xmlns="http://www.w3.org/2000/svg"
                        xmlns:xlink="http://www.w3.org/1999/xlink"
                        aria-hidden="true"
                        role="img"
                        width="100"
                        height="100"
                        preserveAspectRatio="xMidYMid meet"
                        viewBox="0 0 24 24"
                      >
                        <path
                          d="M12 2.247a10 10 0 0 0-3.162 19.487c.5.088.687-.212.687-.475c0-.237-.012-1.025-.012-1.862c-2.513.462-3.163-.613-3.363-1.175a3.636 3.636 0 0 0-1.025-1.413c-.35-.187-.85-.65-.013-.662a2.001 2.001 0 0 1 1.538 1.025a2.137 2.137 0 0 0 2.912.825a2.104 2.104 0 0 1 .638-1.338c-2.225-.25-4.55-1.112-4.55-4.937a3.892 3.892 0 0 1 1.025-2.688a3.594 3.594 0 0 1 .1-2.65s.837-.262 2.75 1.025a9.427 9.427 0 0 1 5 0c1.912-1.3 2.75-1.025 2.75-1.025a3.593 3.593 0 0 1 .1 2.65a3.869 3.869 0 0 1 1.025 2.688c0 3.837-2.338 4.687-4.563 4.937a2.368 2.368 0 0 1 .675 1.85c0 1.338-.012 2.413-.012 2.75c0 .263.187.575.687.475A10.005 10.005 0 0 0 12 2.247z"
                          fill="currentColor"
                        ></path></svg
                    ></a>
                  </td>
                  <td>
                    <h1 style="display: inline-block !important">
                      Contáctanos
                    </h1>
                  </td>
                </tr>
              </tbody>
            </table>
          </div>
          <div class="text">
            Tus opiniones, felicitaciones, sugerencias o inquietudes son
            importantes para nosotros, por eso colocamos a tu disposición los
            siguientes canales.
          </div>
          <a class="franja"></a>
        </div>
      </div>
      <div class="contenedor3Anidado">
        <div class="sqs-block-content" id="yui_3_17_2_1_1656903651806_701">
          <h2 style="white-space: pre-wrap">Contáctanos</h2>
          <p>
            <strong>EMAIL:</strong>
            <a href="mailto:johnalexandermf@gmail.com"
              >johnalexandermf@gmail.com</a
            >
          </p>
          <p>
            <strong>TIENDA ONLINE:</strong>
            <a href="https://www.illustrated.co.nz" target="_blank"
              >TiendasColombia.co.nz</a
            ><br /><strong>FACEBOOK:</strong>
            <a
              href="https://www.facebook.com/kuwithekiwi"
              target="_blank"
              id="yui_3_17_2_1_1656903651806_724"
              >facebook.com/kuwithekiwi</a
            >
          </p>
        </div>
      </div>
    </div>
    <div>
      Nemo non minus rem, facilis, suscipit vero sunt laborum atque debitis
      neque nobis minima ex totam laudantium! Repellat, harum voluptates.
    </div>
    <div>
      Eligendi, tempora omnis voluptatibus cumque eveniet iure voluptates
      sapiente architecto praesentium non blanditiis. Iure voluptatem nobis odio
      magni distinctio aut.
    </div>
    <div>
      Similique velit adipisci omnis, minima sit saepe numquam illum atque eum
      in repellat commodi temporibus eligendi tenetur recusandae nemo
      consequuntur.
    </div>
    <div>
      Animi fuga magnam incidunt voluptatibus accusantium quas. At deserunt
      quasi molestias consectetur eligendi, ipsum esse cum fugiat. Commodi,
      quidem quis!
    </div>
    <div class="contenedor2">
    </div>
  </div>
</template>

<style>
/* .grid > div {
  background: #ecf0f1;
  padding: 1rem;
}
.grid > div:hover {
  border: 1px solid red;
} */
* {
  margin: 0;
  padding: 0;
}
body {
  background: #ffcc33b3;
  /* background: #ffcc33de; */
  color: #000;
  font-family: Arial, Helvetica, sans-serif;
}
.pcontenedor2 {
  display: block;
  margin-block-start: 1em;
  margin-block-end: 1em;
  margin-inline-start: 0px;
  margin-inline-end: 0px;
  text-align: justify;
}
/* creando las grillas que estan dentro de la clase grid */
.grid {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 1em;
  grid-template-rows: auto;
}
.contenedor1 {
  grid-column: 1/5;
}
.contenedor2 {
  grid-column: 1/5;
  text-align: center;
  margin: auto 3em;
  padding: 20px 50px 20px;
}
.contenedor3 {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  grid-auto-rows: auto;
  grid-column: 1/5;
  /* gap: 1em; */
}
.contenedor3 > div {
  /* border: 1px solid #FFD24D; */
  background: #ffffff;
  padding: 1em;
}
hr {
  height: 2px;
  background-color: #000;
  margin: 0%;
}
/* ---------------------------------------------------------------- */
/* configuracion de titulos */
h1 {
  font-family: "Lato", sans-serif;
  font-size: 46px;
  line-height: 1.2;
  font-weight: 300;
  margin-bottom: 30px;
  color: #424242;
}
h2 {
  font-family: "Lato", sans-serif;
  font-size: 46px;
  line-height: 1.2;
  font-weight: 300;
  margin-bottom: 30px;
  color: #424242;
}
h3 {
  font-family: "Lato", sans-serif;
  font-size: 18px;
  line-height: 1.2;
  font-weight: 300;
  margin-bottom: 30px;
  color: #424242;
}
h4 {
  color: #4f4866;
  font-weight: normal;
  font-size: 25px;
  font-family: Arial;
  text-transform: lowercase;
}
h5 {
  color: #656172;
  font-weight: normal;
  font-size: 20px;
  font-family: Arial;
  text-transform: lowercase;
}
h6 {
  color: #747377;
  font-weight: normal;
  font-size: 18px;
  font-family: Arial;
  text-transform: lowercase;
}
p {
  font-family: "Lato", sans-serif;
  display: block;
  margin-block-start: 1em;
  margin-block-end: 1em;
  margin-inline-start: 0px;
  margin-inline-end: 0px;
}

/* ---------------------------------------------------------------- */
</style>