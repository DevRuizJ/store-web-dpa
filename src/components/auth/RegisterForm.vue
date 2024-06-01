<template>
  <div class="container">
    <h2>Formulario de Registro</h2>
    <form action="/ruta_del_backend" method="POST">
      <div class="form-group">
        <label for="firstName">Nombre:</label>
        <input type="text" id="firstName" name="firstName" required />
      </div>
      <div class="form-group">
        <label for="lastName">Apellido:</label>
        <input type="text" id="lastName" name="lastName" required />
      </div>
      <div class="form-group">
        <label for="dateOfBirth">Fecha de Nacimiento:</label>
        <input type="date" id="dateOfBirth" name="dateOfBirth" required />
      </div>
      <div class="form-group">
        <label for="country">País:</label>
        <input type="text" id="country" name="country" required />
      </div>
      <div class="form-group">
        <label for="address">Dirección:</label>
        <input type="text" id="address" name="address" required />
      </div>
      <div class="form-group">
        <label for="email">Correo Electrónico:</label>
        <input type="email" id="email" name="email" required />
      </div>
      <div class="form-group">
        <label for="password">Contraseña:</label>
        <input type="password" id="password" name="password" required />
      </div>
      <div class="form-group">
        <input type="submit" value="Registrar" />
      </div>
    </form>
  </div>
</template>

<style>
body {
  font-family: Arial, sans-serif;
  background-color: #f0f0f0;
  margin: 0;
  padding: 20px;
}
.container {
  max-width: 500px;
  margin: 0 auto;
  background-color: #fff;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}
.form-group {
  margin-bottom: 15px;
}
.form-group label {
  display: block;
  margin-bottom: 5px;
}
.form-group input,
.form-group select {
  width: 100%;
  padding: 8px;
  box-sizing: border-box;
}
.form-group input[type='submit'] {
  background-color: #4caf50;
  color: white;
  border: none;
  cursor: pointer;
}
.form-group input[type='submit']:hover {
  background-color: #45a049;
}
</style>
