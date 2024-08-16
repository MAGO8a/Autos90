<template>
  <div class="app-container">
    <div
      style="display: flex; flex-direction: column; justify-content: center; align-items: center"
    >
      <div class="title-container">
        <div
          style="
            display: flex;
            flex-direction: row;
            justify-content: center;
            align-items: center;
            width: 100%;
          "
        >
          <span class="text-h5">
            <h1>A90</h1>
          </span>
        </div>
        <div
          style="
            display: flex;
            flex-direction: row; /* Cambia de columna a fila */
            justify-content: center;
            align-items: center;
            font-size: 40px;
          "
        >
          <h2>Escuela de Automovilismo</h2>
        </div>
        <div class="image-lines"></div>
      </div>
      <div>
        <img class="custom-image" src="../assets/fiat.jpeg" />
        <!-- Nuevo div para las líneas -->
      </div>

      <span class="text-subtitle-1"
        >En A90, nuestra misión es formar a los nuevos conductores con excelencia. Como institución
        profesional y comprometida, nos esforzamos por garantizar que cada estudiante matriculado
        obtenga su licencia de conducir en el menor tiempo posible, siempre considerando sus
        capacidades individuales.</span
      >

      <div class="image-lines2"></div>
    </div>
  </div>
</template>

<style scoped>
.text-h5 {
  display: flex;
  text-align: center;
  font-size: 50px;
  height: 120px;
}

.text-subtitle-1 {
  font-size: 30px;
  text-align: center;
  margin-top: 30px;
  margin-bottom: 60px;
  width: 50%;
  color: #ffffff;
}

.custom-image {
  width: 500px; /* Ajusta esto al tamaño deseado */
  height: auto; /* Mantiene la proporción de la imagen */
  border-radius: 15px;
  margin-top: 30px;
}

.title-container {
  color: #ffffff;
  background-color: rgba(255, 255, 255, 0);
  padding-left: 20px;
  padding-right: 20px;
}

.image-lines {
  border-top: 2px solid #ffffff; /* Línea superior */
  border-bottom: 2px solid #ffffff; /* Línea inferior */
  width: 100%; /* Asegura que las líneas cubran todo el ancho de la imagen */
}

.image-lines2 {
  border-top: 2px solid #ffffff; /* Línea superior */
  border-bottom: 2px solid #ffffff; /* Línea inferior */
  width: 80%; /* Asegura que las líneas cubran todo el ancho de la imagen */
}
</style>
