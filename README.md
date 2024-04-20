# ver-anuncios-
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Primera Página Web</title>
    <meta name="description" content="Descripción de tu página aquí">
    <meta name="keywords" content="palabra clave 1, palabra clave 2, palabra clave 3">
    <meta name="author" content="Nombre del autor">
    <link rel="social" href="URL de tu perfil en la red social">

    <!-- Etiqueta viewport para dispositivos móviles -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <!-- Estilos CSS -->
    <style>
        body {
            font-family: Arial, sans-serif; /* Fuente predeterminada */
            color: #333; /* Color de texto */
            background-color: #f9f9f9; /* Color de fondo */
            margin: 0; /* Elimina el margen exterior */
            padding: 0; /* Elimina el relleno */
        }

        header, footer {
            background-color: #007bff; /* Color de fondo del encabezado y pie de página */
            color: #fff; /* Color de texto del encabezado y pie de página */
            text-align: center; /* Centrar el texto */
            padding: 20px 0; /* Espaciado interno */
            animation: fadeInDown 1s ease; /* Animación de entrada */
        }

        main {
            text-align: center; /* Centrar el texto */
            padding: 20px; /* Espaciado interno */
            animation: fadeInUp 1s ease; /* Animación de entrada */
        }

        /* Animación de entrada para el encabezado y pie de página */
        @keyframes fadeInDown {
            from {
                opacity: 0;
                transform: translateY(-20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        /* Animación de entrada para el contenido principal */
        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>PÁGINA PARA VER ANUNCIOS:)</h1>
    </header>
    <main>
        <h2>Sobre Nosotros</h2>
        <p>Somos una página web dedicada a ganar dinero con publicidad</p>
        
        <!-- Aquí puedes pegar el código de inserción del anuncio de Google AdSense -->
        <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script>
        <ins class="adsbygoogle"
             style="display:block"
             data-ad-client="tu-id-de-cliente"
             data-ad-slot="tu-id-de-slot"
             data-ad-format="auto"
             data-full-width-responsive="true"></ins>
        <script>
             (adsbygoogle = window.adsbygoogle || []).push({});
        </script>
        
    </main>
    <footer>
        <p>Derechos de autor &copy; 2024 Unu~sanchez</p>
    </footer>
    <!-- Código de Google Analytics -->
    <script async src="https://www.googletagmanager.com/gtag/js?id=G-H96J010H01"></script>
    <script>
      window.dataLayer = window.dataLayer || [];
      function gtag(){dataLayer.push(arguments);}
      gtag('js', new Date());

      gtag('config', 'G-H96J010H01');
    </script>
</body>
</html>
