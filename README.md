<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Tabla de Animales</title>

<style>

body{
    font-family: 'Segoe UI', sans-serif;
    background: linear-gradient(120deg,#667eea,#764ba2);
    margin:0;
    padding:40px;
    color:white;
}

h1{
    text-align:center;
    margin-bottom:30px;
}

table{
    width:85%;
    margin:auto;
    border-collapse:collapse;
    background:white;
    color:#333;
    border-radius:15px;
    overflow:hidden;
    box-shadow:0 15px 30px rgba(0,0,0,0.3);
}

th{
    background: linear-gradient(90deg,#ff7e5f,#feb47b);
    color:white;
    padding:15px;
    font-size:18px;
    text-transform:uppercase;
}

td{
    padding:15px;
    text-align:center;
}

tr:nth-child(even){
    background:#f4f6ff;
}

tr:hover{
    background:#ffe0d6;
    transform:scale(1.01);
    transition:0.3s;
}

img{
    width:100px;
    height:100px;
    object-fit:cover;
    border-radius:12px;
    border:3px solid #ff7e5f;
    transition:0.3s;
}

img:hover{
    transform:scale(1.15);
    border-color:#764ba2;
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
<td>Animal doméstico conocido por su gran lealtad al ser humano.</td>
</tr>

<tr>
<td><img src="https://upload.wikimedia.org/wikipedia/commons/3/3a/Cat03.jpg"></td>
<td>Gato</td>
<td>Felino doméstico ágil, curioso e independiente.</td>
</tr>

<tr>
<td><img src="https://upload.wikimedia.org/wikipedia/commons/7/73/Lion_waiting_in_Namibia.jpg"></td>
<td>León</td>
<td>Gran felino africano conocido como el rey de la selva.</td>
</tr>

<tr>
<td><img src="https://upload.wikimedia.org/wikipedia/commons/3/37/African_Bush_Elephant.jpg"></td>
<td>Elefante</td>
<td>El mamífero terrestre más grande del planeta.</td>
</tr>

<tr>
<td><img src="https://upload.wikimedia.org/wikipedia/commons/e/e0/Emperor_penguin.jpg"></td>
<td>Pingüino</td>
<td>Ave que no vuela y es excelente nadadora.</td>
</tr>

<tr>
<td><img src="https://upload.wikimedia.org/wikipedia/commons/5/56/Tiger.50.jpg"></td>
<td>Tigre</td>
<td>Felino salvaje famoso por sus rayas negras.</td>
</tr>

<tr>
<td><img src="https://upload.wikimedia.org/wikipedia/commons/9/9f/Giraffe_standing.jpg"></td>
<td>Jirafa</td>
<td>Animal africano conocido por su cuello largo.</td>
</tr>

<tr>
<td><img src="https://upload.wikimedia.org/wikipedia/commons/0/0f/Zebra_Botswana_edit02.jpg"></td>
<td>Cebra</td>
<td>Animal con rayas blancas y negras único en África.</td>
</tr>

<tr>
<td><img src="https://upload.wikimedia.org/wikipedia/commons/0/0f/Grosser_Panda.JPG"></td>
<td>Panda</td>
<td>Oso originario de China que se alimenta de bambú.</td>
</tr>

<tr>
<td><img src="https://upload.wikimedia.org/wikipedia/commons/4/49/Koala_climbing_tree.jpg"></td>
<td>Koala</td>
<td>Mamífero australiano que vive en árboles de eucalipto.</td>
</tr>

</table>

</body>
</html>
