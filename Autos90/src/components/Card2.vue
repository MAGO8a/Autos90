<template>
  <div class="cards-container">
    <div class="card-container">
      <span class="title-card1"
        ><img src="../assets/diamond.png" style="margin-right: 10px" />Calidad del servicio</span
      >

      <div class="image-lines2"></div>

      <span class="text-subtitle-1">
        Nos comprometemos a ofrecer una formación de alta calidad, asegurando que cada estudiante
        reciba la mejor educación vial posible.
      </span>
    </div>
    <div class="card-container">
      <span class="title-card2"
        ><img src="../assets/thumbs-up-trust.png" style="margin-right: 10px" />Confianza</span
      >

      <div class="image-lines2"></div>

      <span class="text-subtitle-1"
        >Desarrollamos nuestro trabajo de manera que nuestros estudiantes ganen confianza y
        disciplina al manejar, asegurando que se sientan seguros y preparados en cualquier situación
        vial.
      </span>
    </div>
    <div class="card-container">
      <span class="title-card"
        ><img src="../assets/tools.png" style="margin-right: 10px" />Trabajo
        personalizado</span>

      <div class="image-lines2"></div>

      <span class="text-subtitle-1"
        >Adaptamos nuestra enseñanza a las características individuales de cada cliente, asegurando
        una experiencia de aprendizaje personalizada y efectiva.
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
  margin-bottom: 80px;
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
  border-top: 2px solid #0d4fb3; /* Línea superior */
  border-bottom: 2px solid #0d4fb3; /* Línea inferior */
  width: 80%; /* Asegura que las líneas cubran todo el ancho de la imagen */
}

.title-card2 {
  margin-top: 30px;
}

.title-card1 {
  margin-top: 10px;
}
</style>
