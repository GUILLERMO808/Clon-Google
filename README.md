```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Clon de Google</title>
    <style>
        /* Configura el cuerpo */
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            margin: 0;
            background-color: #f2f2f2;
            position: relative;
        }

        /* Estilo para la imagen de perfil */
        .profile-pic {
            position: absolute;
            top: 10px;
            right: 10px;
            width: 40px;
            height: 40px;
            border-radius: 50%; /* Hace que la imagen sea circular */
            object-fit: cover; /* Asegura que la imagen se ajuste dentro del círculo */
            cursor: pointer; /* Cursor de mano como en Google */
        }

        /* Caja de búsqueda */
        .search-box {
            display: flex;
            flex-direction: column;
            align-items: center;
            text-align: center;
        }

        /* Logo de Google */
        .google-logo {
            font-size: 2rem;
            color: #4285F4;
            font-weight: bold;
            margin-bottom: 20px;
        }

        /* Barra de búsqueda */
        .search-bar {
            width: 400px;
            padding: 10px;
            border: 1px solid #dcdcdc;
            border-radius: 24px;
            font-size: 16px;
        }
    </style>
</head>
<body>

    <!-- Caja de búsqueda y logo -->
    <div class="search-box">
        <div class="google-logo">Google</div>
        <input type="text" class="search-bar" placeholder="Buscar en Google">
    </div>

    <!-- Imagen de perfil -->
    <img src="https://lh3.googleusercontent.com/a/ACg8ocIbwxxvqEqTqv-5AIV1_7DuyMTUPoPW17DKzY2Sc-1tzHSWxLg=s288-c-no" alt="Foto de perfil" class="profile-pic">

</body>
</html>
