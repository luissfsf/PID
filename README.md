# PID

Primera pagina web


<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="one.css">
    <title>Página Principal</title>
</head>
<body>
    <div class="title">
        <h1>Registro de Vacunación</h1>
    </div>
    
    <div class="container">
        <div class="options">
            <a href="dos.html" class="button">Autenticarse</a>
            <a href="tres.html" class="button">Registrarse</a>
            
            <a href="#" class="button">Menú</a>
        </div>
    </div>
</body>
</html>


.title {
    text-align: center;
    margin-bottom: 20px;
}

.title h1 {
    font-size: 50px;
    color: white;
    text-shadow: 2px 2px 5px black;
}


body, html {
    height: 100%;
    margin: 0;
    font-family: Arial, sans-serif;
}


.container {
    background-image: url('1.jpg'); /* Nombre de la imagen de fondo */
    height: 100%;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    display: flex;
    justify-content: center;
    align-items: center;
}

.options {
    text-align: center;
}

.button {
    display: inline-block;
    padding: 15px 30px;
    margin: 10px;
    font-size: 20px;
    color: white;
    background-color: rgba(0, 0, 0, 0.5);
    text-decoration: none;
    border-radius: 5px;
    transition: background-color 0.3s;
}

.button:hover {
    background-color: rgba(0, 0, 0, 0.8);
}



Segunda pagina web

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="two.css">
    <title>dos</title>
</head>
<body>
    <div class="container">
        <div class="login-box">
            <h2>Autenticarse</h2>
            <form action="cuatro.html" method="get">
                <div class="textbox">
                    <input type="text" placeholder="User" name="user" required>
                </div>
                <div class="textbox">
                    <input type="password" placeholder="Password" name="password" required>
                </div>
                <button type="submit" class="btn">Login</button>
            </form>
        </div>
    </div>
</body>
</html>


body, html {
    height: 100%;
    margin: 0;
    font-family: Arial, sans-serif;
}

.container {
    background-image: url('2.jpg'); /* Nombre de la imagen de fondo */
    height: 100%;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    display: flex;
    justify-content: center;
    align-items: center;
}

.login-box {
    width: 300px;
    padding: 40px;
    position: absolute;
    background: rgba(0, 0, 0, 0.8);
    text-align: center;
    border-radius: 10px;
    box-shadow: 0 15px 25px rgba(0, 0, 0, 0.5);
}

.login-box h2 {
    margin: 0 0 30px;
    padding: 0;
    color: white;
    text-transform: uppercase;
    font-size: 22px;
}

.textbox {
    position: relative;
    margin-bottom: 30px;
}

.textbox input {
    width: 100%;
    padding: 10px;
    background: none;
    border: none;
    border-bottom: 2px solid white;
    outline: none;
    color: white;
    font-size: 18px;
}

.textbox input::placeholder {
    color: rgba(255, 255, 255, 0.5);
}

.btn {
    width: 100%;
    background: none;
    border: 2px solid white;
    color: white;
    padding: 10px;
    font-size: 18px;
    cursor: pointer;
    border-radius: 5px;
    transition: background 0.3s, color 0.3s;
}

.btn:hover {
    background: white;
    color: black;
}



Tercera



<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="tree.css">
    <title>Registrarse</title>
</head>
<body>
    <div class="container">
        <div class="register-box">
            <h2>Registrarse</h2>
            <form>
                <div class="textbox">
                    <input type="text" placeholder="Nombre" name="nombre" required>
                </div>
                <div class="textbox">
                    <input type="text" placeholder="Apellido" name="apellido" required>
                </div>
                <div class="textbox">
                    <select name="rol" required>
                        <option value="Enfermera">Enfermera</option>
                        <option value="Medico">Medico</option>
                        <option value="Estadista de Salud">Estadista de Salud</option>
                    </select>
                </div>
                <div class="textbox">
                    <input type="text" placeholder="User" name="user" required>
                </div>
                <div class="textbox">
                    <input type="password" placeholder="Password" name="password" required>
                </div>
                <button type="submit" class="btn">Confirmar</button>
            </form>
        </div>
    </div>
</body>
</html>


body, html {
    height: 100%;
    margin: 0;
    font-family: Arial, sans-serif;
}

.container {
    background-image: url('3.jpg'); /* Nombre de la imagen de fondo */
    height: 100%;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    display: flex;
    justify-content: center;
    align-items: center;
}

.register-box {
    width: 300px;
    padding: 40px;
    background: rgba(0, 0, 0, 0.8);
    text-align: center;
    border-radius: 10px;
    box-shadow: 0 15px 25px rgba(0, 0, 0, 0.5);
}

.register-box h2 {
    margin: 0 0 30px;
    padding: 0;
    color: white;
    text-transform: uppercase;
    font-size: 22px;
}

.textbox {
    position: relative;
    margin-bottom: 30px;
}

.textbox input, .textbox select {
    width: 100%;
    padding: 10px;
    background: none;
    border: none;
    border-bottom: 2px solid white;
    outline: none;
    color: white;
    font-size: 18px;
}

.textbox input::placeholder, .textbox select {
    color: rgba(255, 255, 255, 0.5);
    background: none;
}

.btn {
    width: 100%;
    background: none;
    border: 2px solid white;
    color: white;
    padding: 10px;
    font-size: 18px;
    cursor: pointer;
    border-radius: 5px;
    transition: background 0.3s, color 0.3s;
}

.btn:hover {
    background: white;
    color: black;
}



     Cuarta



     
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="four.css">
    <title>Tarjeta de Vacunación</title>
</head>
<body>
    <div class="title">
        <h1></h1>
    </div>
    
    <div class="container">
        <div class="register-box">
            <h2>Tarjeta de Vacunación</h2>
            <form>
                <div class="textbox">
                    <input type="text" placeholder="Nombre y apellidos" name="nombre" required>
                </div>
                <div class="textbox">
                    <input type="text" placeholder="Municipio" name="municipio" required>
                </div>
                <div class="textbox">
                    <input type="text" placeholder="Vacunatorio" name="vacunatorio" required>
                </div>
                <div class="textbox">
                    <input type="text" placeholder="Lote" name="lote" required>
                </div>
                <div class="textbox">
                    <input type="date" placeholder="Fecha" name="fecha" required>
                </div>
                <div class="textbox">
                    <input type="time" placeholder="Hora" name="hora" required>
                </div>
                <div class="textbox">
                    <input type="text" placeholder="Dosis" name="dosis" required>
                </div>
                <div class="textbox">
                    <input type="text" placeholder="Nombre del Vacunador" name="nombre_vacunador" required>
                </div>
                <button type="submit" class="btn">Registrar</button>
                </div>
            <div class="buttons">
                
                <button type="button" class="btn-hcg" onclick="location.href='cinco.html'">Acceder a HCG</button>
            </div>
            
            </form>
        </div>
    </div>
</body>
</html>

.title {
    text-align: center;
    margin-bottom: 20px;
}

.title h1 {
    font-size: 50px;
    color: white;
    text-shadow: 2px 2px 5px black;
}


body, html {
    height: 100%;
    margin: 0;
    font-family: Arial, sans-serif;
}

.container {
    background-image: url('4.jpg'); /* Nombre de la imagen de fondo */
    height: 100%;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    display: flex;
    justify-content: center;
    align-items: center;
}

.register-box {
    width: 300px;
    padding: 40px;
    background: rgba(0, 0, 0, 0.8);
    text-align: center;
    border-radius: 10px;
    box-shadow: 0 15px 25px rgba(0, 0, 0, 0.5);
}

.register-box h2 {
    margin: 0 0 30px;
    padding: 0;
    color: white;
    text-transform: uppercase;
    font-size: 22px;
}

.textbox {
    position: relative;
    margin-bottom: 30px;
}

.textbox input {
    width: 100%;
    padding: 10px;
    background: none;
    border: none;
    border-bottom: 2px solid white;
    outline: none;
    color: white;
    font-size: 18px;
}

.textbox input::placeholder {
    color: rgba(255, 255, 255, 0.5);
}

.btn {
    width: 100%;
    background: none;
    border: 2px solid white;
    color: white;
    padding: 10px;
    font-size: 18px;
    cursor: pointer;
    border-radius: 5px;
    transition: background 0.3s, color 0.3s;
}

.btn:hover {
    background: white;
    color: black;
}
    .buttons {
        display: flex;
        justify-content: space-between;
    }
    
    .btn-hcg {
        flex: 1;
        margin-right: 10px;
        padding: 20px;
        background: none;
        border: 2px solid white;
        color: white;
        font-size: 18px;
        cursor: pointer;
        border-radius: 5px;
        transition: background 0.3s, color 0.3s;
        text-align: center;
    }
    
    .btn-hcg:hover {
        background: white;
        color: black;
    }
    
}


  Quinta



  
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="five.css">
    <title>Historias Clínicas Generales</title>
</head>
<body>
    <div class="container">
        <div class="hcg-box">
            <h2>Historias Clínicas Generales</h2>
            <form>
                <div class="textbox">
                    <input type="text" placeholder="Nombre y Apellidos" name="nombre_apellidos" required>
                </div>
                
              
                <button type="submit" class="btn">Buscar</button>
            </form>
        </div>
    </div>
</body>
</html>


body, html {
    height: 100%;
    margin: 0;
    font-family: Arial, sans-serif;
}

.container {
    background-image: url('5.jpg'); /* Nombre de la imagen de fondo */
    height: 100%;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    display: flex;
    justify-content: center;
    align-items: center;
}

.hcg-box {
    width: 400px;
    padding: 40px;
    background: rgba(0, 0, 0, 0.8);
    text-align: center;
    border-radius: 10px;
    box-shadow: 0 15px 25px rgba(0, 0, 0, 0.5);
}

.hcg-box h2 {
    margin: 0 0 30px;
    padding: 0;
    color: white;
    text-transform: uppercase;
    font-size: 22px;
}

.textbox {
    position: relative;
    margin-bottom: 30px;
}

.textbox input, .textbox textarea {
    width: 100%;
    padding: 10px;
    background: none;
    border: none;
    border-bottom: 2px solid white;
    outline: none;
    color: white;
    font-size: 18px;
}

.textbox textarea {
    height: 100px;
    resize: none;
}

.textbox input::placeholder, .textbox textarea::placeholder {
    color: rgba(255, 255, 255, 0.5);
}

.btn {
    width: 100%;
    background: none;
    border: 2px solid white;
    color: white;
    padding: 10px;
    font-size: 18px;
    cursor: pointer;
    border-radius: 5px;
    transition: background 0.3s, color 0.3s;
}

.btn:hover {
    background: white;
    color: black;
}



