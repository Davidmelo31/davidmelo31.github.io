<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Mi Tarjeta Personal</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }
    .card {
      background-color: white;
      padding: 30px;
      border-radius: 12px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      text-align: center;
      width: 300px;
    }
    .card h2 {
      color: #333;
    }
    .card p {
      color: #666;
      margin: 10px 0 20px;
    }
    .card button {
      padding: 10px 20px;
      border: none;
      background-color: #007BFF;
      color: white;
      border-radius: 6px;
      cursor: pointer;
    }
    .card button:hover {
      background-color: #0056b3;
    }
  </style>
</head>
<body>
  <div class="card">
    <h2>Melito García</h2>
    <p>Estudiante de Ingeniería de Sistemas,</p>
    <button onclick="alert('¡Gracias por contactarme!')">Contáctame</button>
  </div>
</body>
</html>
