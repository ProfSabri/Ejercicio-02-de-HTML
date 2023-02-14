# Ejercicio-02-de-HTML
Segundo ejercicio bootcamp
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ejercicio 02 - Formularios en HTML</title>
</head>
<body>
    <form action="/">
        <div>
            <label for="nombre">Nombre</label>
            <input type="text" name="nombre" id="nombre" >
        </div>
        <br>

        <div>
            <label for="edad">Edad?</label>
            <input type="number" name="edad" id="edad" min="0" max="150">
        </div>
        <br>

        <div>
            <label for="frase">Frase favorita</label>
            <textarea name="frase" id="frase"></textarea>
        </div>
        <br>

        <div>
            <button type="submit">Enviar</button>
            <button type="reset">Reset</button>
        </div>
        <br>

    </form>
</body>
</html>
