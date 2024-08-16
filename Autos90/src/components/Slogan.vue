<template>
  <div class="card-container">
    <img src="../assets/snap.png" style="margin-top: 40px; margin-bottom: 5px" />
    <span class="title-card">Hazlo fácil!</span>
  </div>
  <span class="text-subtitle-1"
    >Tenemos el compromiso de proporcionar una formación de conductores accesible y eficiente.
    Obtener una licencia de conducir no tiene por qué ser un proceso complicado o estresante.
    Simplificamos y facilitar cada paso del camino, adaptándose a las capacidades individuales,
    formando conductores y promoviendo una conducción segura y responsable.
  </span>
</template>

<style scoped>
.card-container {
  display: flex;
  flex-direction: column; /* Cambia de fila a columna para que el texto se apile verticalmente */
  justify-content: center;
  align-items: center;
  font-size: 60px;
  margin: 30px;
  width: 30%;
  color: #000000;
  background-color: #ffffff;
  gap: 20px;
  border-radius: 150%;
}

.title-card {
  margin-bottom: 50px;
}

.text-subtitle-1 {
  font-size: 30px;
  text-align: center;
  margin-top: 30px;
  margin-bottom: 60px;
  width: 70%;
  color: #ffffff;
}
</style>
