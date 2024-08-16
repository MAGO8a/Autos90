<template>
  <div class="cards-container">
    <div class="card-container">
      <span class="title-card1"><img src="../assets/challenge.png" style="margin-right: 10px;">Misión</span>

      <div class="image-lines2"></div>

      <span class="text-subtitle-1"
        >En A90, nuestra misión es formar a los nuevos conductores con excelencia. Como institución
        profesional y comprometida, nos esforzamos por garantizar que cada estudiante matriculado
        obtenga su licencia de conducir en el menor tiempo posible, siempre considerando sus
        capacidades individuales.
      </span>
    </div>
    <div class="card-container">
      <span class="title-card2"><img src="../assets/vision.png" style="margin-right: 10px;">Visión</span>

      <div class="image-lines2"></div>

      <span class="text-subtitle-1"
        >Ser la institución líder en la formación de conductores, reconocida por nuestra excelencia
        y compromiso en la educación vial. Aspiramos a que cada estudiante no sólo obtenga su
        licencia de conducir de manera eficiente, sino que también desarrolle habilidades y
        conocimientos que promuevan una conducción segura y responsable.
      </span>
    </div>
    <div class="card-container">
      <span class="title-card"><img src="../assets/benefit-diamond-alt.png" style="margin-right: 10px;">Propuesta de valor</span>

      <div class="image-lines2"></div>

      <span class="text-subtitle-1"
        >En A90, no solo enseñamos a conducir; forjamos conductores excepcionales. Nuestro
        compromiso es claro: acelerar tu camino hacia la licencia de conducir, adaptándonos a tus
        habilidades individuales. Al hacerlo, no solo creamos conductores, sino guardianes de la
        seguridad vial.
      </span>
    </div>
  </div>
</template>

<style scoped>
.cards-container {
  display: flex;
  flex-wrap: wrap; /* Permite que los elementos se envuelvan si hay demasiados para caber en una sola línea */
  justify-content: space-between; /* Distribuye el espacio igualmente entre los elementos */
  align-items: stretch; /* Hace que los elementos hijos se estiren para llenar el contenedor */
  font-size: 30px;
  margin: 30px;
  width: 100%; /* Asegúrate de que el contenedor ocupe todo el ancho disponible */
  color: #000000;
}

.card-container {
  display: flex;
  flex-direction: column; /* Cambia de fila a columna para que el texto se apile verticalmente */
  justify-content: center;
  align-items: center;
  font-size: 30px;
  margin: 30px;
  width: 30%;
  color: #000000;
  background-color: #ffffff;
  gap: 20px;
  border-radius: 15px;
}

.text-subtitle-1 {
  margin: 30px;
  font-size: 25px;
  display: flex;
  width: 80%;
  color: #000000;
}

.image-lines2 {
  border-top: 2px solid #0D4FB3; /* Línea superior */
  border-bottom: 2px solid #0D4FB3; /* Línea inferior */
  width: 80%; /* Asegura que las líneas cubran todo el ancho de la imagen */
}

.title-card2{
    margin-top: 30px;
}

.title-card1{
    margin-top: 30px;
}
</style>
