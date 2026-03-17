<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Proyecto.1</title>

<style>
body{
    font-family: 'Segoe UI', sans-serif;
    background: linear-gradient(135deg, #4facfe, #00f2fe);
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}

/* Tabla */
table{
    width: 80%;
    border-collapse: collapse;
    background: white;
    border-radius: 15px;
    overflow: hidden;
    box-shadow: 0 10px 25px rgba(0,0,0,0.2);
}

/* Filas */
tr{
    transition: 0.3s;
}

tr:nth-child(even){
    background-color: #f2f2f2;
}

tr:hover{
    background-color: #d0f0ff;
    transform: scale(1.01);
}

/* Celdas */
td{
    padding: 15px;
    text-align: center;
    color: #333;
    font-weight: 500;
}

/* Imágenes */
img{
    width: 120px;
    height: 90px;
    object-fit: cover;
    border-radius: 10px;
    border: 3px solid #4facfe;
    transition: 0.3s;
}

img:hover{
    transform: scale(1.1);
    border-color: #00c6ff;
}
</style>

</head>

<body>

<table>
<tr>
<td><img src="https://upload.wikimedia.org/wikipedia/commons/6/6e/Golde33443.jpg"></td>
<td>Perro</td>
<td>Animal doméstico conocido por su lealtad.</td>
</tr>

<tr>
<td><img src="https://upload.wikimedia.org/wikipedia/commons/3/3a/Cat03.jpg"></td>
<td>Gato</td>
<td>Felino doméstico ágil e independiente.</td>
</tr>

<tr>
<td><img src="https://upload.wikimedia.org/wikipedia/commons/7/73/Lion_waiting_in_Namibia.jpg"></td>
<td>León</td>
<td>Gran felino africano conocido como rey de la selva.</td>
</tr>

<tr>
<td><img src="https://upload.wikimedia.org/wikipedia/commons/3/37/African_Bush_Elephant.jpg"></td>
<td>Elefante</td>
<td>El mamífero terrestre más grande.</td>
</tr>

<tr>
<td><img src="https://upload.wikimedia.org/wikipedia/commons/e/e0/Emperor_penguin.jpg"></td>
<td>Pingüino</td>
<td>Ave que no vuela y nada muy bien.</td>
</tr>

<tr>
<td><img src="https://upload.wikimedia.org/wikipedia/commons/5/56/Tiger.50.jpg"></td>
<td>Tigre</td>
<td>Felino salvaje con rayas negras.</td>
</tr>

<tr>
<td><img src="https://upload.wikimedia.org/wikipedia/commons/9/9f/Giraffe_standing.jpg"></td>
<td>Jirafa</td>
<td>Animal africano de cuello largo.</td>
</tr>

<tr>
<td><img src="https://upload.wikimedia.org/wikipedia/commons/0/0f/Zebra_Botswana_edit02.jpg"></td>
<td>Cebra</td>
<td>Animal con rayas negras y blancas.</td>
</tr>

<tr>
<td><img src="https://upload.wikimedia.org/wikipedia/commons/0/0f/Grosser_Panda.JPG"></td>
<td>Panda</td>
<td>Oso que come principalmente bambú.</td>
</tr>

<tr>
<td><img src="https://upload.wikimedia.org/wikipedia/commons/4/49/Koala_climbing_tree.jpg"></td>
<td>Koala</td>
<td>Mamífero australiano que vive en árboles.</td>
</tr>
</table>

</body>
</html>
