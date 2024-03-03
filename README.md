<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Ejemplo de Tabla Azul</title>
<style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f0f0f0;
    }
    h1 {
      color: #333;
    }
    p {
      color: #666;
    }
    .destacado {
      font-weight: bold;
      color: #ff0000;
    }
    table {
      border-collapse: collapse;
      width: 100%;
      max-width: 600px; /* Ancho máximo para evitar que la tabla se expanda demasiado en pantallas grandes */
      margin: 20px auto; /* Centrar la tabla horizontalmente */
      background-color: #007bff; /* Color de fondo azul */
      color: white; /* Color del texto blanco */
    }
    th, td {
      border: 1px solid white; /* Borde blanco */
      padding: 8px; /* Espaciado interno */
      text-align: center; /* Alineación centrada */
    }
    th {
      background-color: #0056b3; /* Color de fondo azul oscuro para encabezados */
    }
    tr:nth-child(even) {
      background-color: #0056b3; /* Color de fondo azul oscuro para filas pares */
    }
</style>
</head>
<body>

<h1>Submissions</h1>

## Introduction

<p>A repository to keep track of problem solving practice, containing solutions from platforms:</p>
<ul>
  <li>Codeforces &nbsp; <a href='https://codeforces.com/profile/Nayperlamp'><img src='https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/codeforces.svg' width='25' height='25'></a></li>
</ul>

## Contents

<table>
    <thead>
        <tr>
            <th>Column 1</th>
            <th>Column 2</th>
            <th>Column 3</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan=4 align="center">R1 Text</td>
            <td rowspan=2 align="center">R2 Text A</td>
            <td align="center">R3 Text A</td>
        </tr>
        <tr>
            <td align="center">R3 Text B</td>
        </tr>
        <tr>
            <td rowspan=2 align="center">R2 Text B</td>
            <td align="center">R3 Text C</td>
        </tr>
        <tr>
            <td align="center">R3 Text D</td>
        </tr>
    </tbody>
</table>

</body>
</html>
