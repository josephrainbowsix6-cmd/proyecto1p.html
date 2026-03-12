<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Galería de Animales</title>

<style>
body{
    font-family: Arial, sans-serif;
    background: linear-gradient(135deg,#74ebd5,#ACB6E5);
    margin:0;
    padding:0;
}

h1{
    text-align:center;
    padding:20px;
    color:#333;
}

table{
    width:80%;
    margin:auto;
    border-collapse:collapse;
    background:white;
    border-radius:10px;
    overflow:hidden;
    box-shadow:0 10px 20px rgba(0,0,0,0.2);
}

th{
    background:#4CAF50;
    color:white;
    padding:15px;
    font-size:18px;
}

td{
    padding:12px;
    text-align:center;
}

tr:nth-child(even){
    background:#f2f2f2;
}

img{
    width:100px;
    height:100px;
    object-fit:cover;
    border-radius:10px;
}

tr:hover{
    background:#e8f5e9;
}
</style>

</head>
<body>

<h1>🐾 Tabla de Animales</h1>

<table>

<tr>
<th>Imagen</th>
<th>Animal</th>
<th>Descripción</th>
</tr>

<tr>
<td><img src="https://source.unsplash.com/100x100/?dog"></td>
<td>Perro</td>
<td>Animal doméstico conocido por su lealtad y compañía.</td>
</tr>

<tr>
<td><img src="https://source.unsplash.com/100x100/?cat"></td>
<td>Gato</td>
<td>Felino doméstico ágil, curioso e independiente.</td>
</tr>

<tr>
<td><img src="https://source.unsplash.com/100x100/?lion"></td>
<td>León</td>
<td>Gran felino africano conocido como el rey de la selva.</td>
</tr>

<tr>
<td><img src="https://source.unsplash.com/100x100/?elephant"></td>
<td>Elefante</td>
<td>El mamífero terrestre más grande del planeta.</td>
</tr>

<tr>
<td><img src="https://source.unsplash.com/100x100/?penguin"></td>
<td>Pingüino</td>
<td>Ave que no vuela y es excelente nadadora.</td>
</tr>

<tr>
<td><img src="https://source.unsplash.com/100x100/?tiger"></td>
<td>Tigre</td>
<td>Felino salvaje famoso por sus rayas negras.</td>
</tr>

<tr>
<td><img src="https://source.unsplash.com/100x100/?giraffe"></td>
<td>Jirafa</td>
<td>Animal africano conocido por su cuello largo.</td>
</tr>

<tr>
<td><img src="https://source.unsplash.com/100x100/?zebra"></td>
<td>Cebra</td>
<td>Animal con rayas blancas y negras único en África.</td>
</tr>

<tr>
<td><img src="https://source.unsplash.com/100x100/?panda"></td>
<td>Panda</td>
<td>Oso originario de China que se alimenta de bambú.</td>
</tr>

<tr>
<td><img src="https://source.unsplash.com/100x100/?koala"></td>
<td>Koala</td>
<td>Mamífero australiano que vive en árboles de eucalipto.</td>
</tr>

</table>

</body>
</html>
