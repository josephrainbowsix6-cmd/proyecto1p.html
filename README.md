<!DOCTYPE html>
<html lang="es">

<head>
<meta charset="UTF-8">
<title>Galería de Animales</title>

<style>

body{
    font-family:'Segoe UI', sans-serif;
    background: linear-gradient(135deg,#0f2027,#203a43,#2c5364);
    margin:0;
    padding:40px;
}

h1{
    text-align:center;
    color:white;
    font-size:40px;
    margin-bottom:30px;
}

table{
    width:90%;
    margin:auto;
    border-collapse:collapse;
    background:white;
    border-radius:15px;
    overflow:hidden;
    box-shadow:0 15px 35px rgba(0,0,0,0.4);
}

th{
    background:linear-gradient(90deg,#ff512f,#dd2476);
    color:white;
    padding:15px;
}

td{
    padding:15px;
    text-align:center;
}

tr:nth-child(even){
    background:#f2f6ff;
}

tr:hover{
    background:#ffe6f0;
}

img{
    width:120px;
    height:120px;
    object-fit:cover;
    border-radius:12px;
    border:3px solid #dd2476;
}

</style>
</head>

<body>

<h1>🐾 Galería de Animales</h1>

<table>

<tr>
<th>Imagen</th>
<th>Animal</th>
<th>Descripción</th>
</tr>

<tr>
<td><img src="https://upload.wikimedia.org/wikipedia/commons/6/6e/Golde33443.jpg"></td>
<td>Perro</td>
<td>Animal doméstico conocido por su lealtad.</td>
</tr>

</table>

</body>
</html>
