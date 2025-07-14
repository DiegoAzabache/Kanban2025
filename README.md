<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Kanban - Proyecto 4Life</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f2f2f2;
      margin: 0;
      padding: 20px;
    }

    h1 {
      text-align: center;
      color: #4CAF50;
    }

    .kanban-board {
      display: flex;
      gap: 20px;
      justify-content: center;
      margin-top: 30px;
    }

    .column {
      background: white;
      border-radius: 8px;
      width: 300px;
      padding: 15px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }

    .column h2 {
      text-align: center;
      border-bottom: 2px solid #ccc;
      padding-bottom: 10px;
    }

    .card {
      background: #e3f2fd;
      border-left: 5px solid #4CAF50;
      padding: 10px;
      margin: 10px 0;
      border-radius: 5px;
    }

    .card strong {
      display: block;
      margin-bottom: 5px;
    }
  </style>
</head>
<body>

<h1>Tablero Kanban - Proyecto Plataforma Afiliados 4Life</h1>

<div class="kanban-board">

  <div class="column">
    <h2>Backlog</h2>
    <div class="card">
      <strong>Historia #1</strong>
      Como afiliado, necesito ver mis estadísticas de ventas, para que pueda optimizar mis campañas.
    </div>
    <div class="card">
      <strong>Historia #2</strong>
      Como nuevo usuario, necesito una guía rápida, para que pueda aprender a usar la plataforma fácilmente.
    </div>
  </div>

  <div class="column">
    <h2>En curso</h2>
    <div class="card">
      <strong>Historia #3</strong>
      Como afiliado, necesito acceder a materiales de marketing, para que pueda promocionar productos fácilmente.
    </div>
  </div>

  <div class="column">
    <h2>Hecho</h2>
    <div class="card">
      <strong>Historia #4</strong>
      Como administrador, necesito aprobar cuentas de afiliados, para que sólo usuarios verificados accedan al sistema.
    </div>
  </div>

</div>

</body>
</html>
