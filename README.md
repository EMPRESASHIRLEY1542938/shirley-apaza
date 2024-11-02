<!DOCTYPE html>
<html lang="es">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EMPRESA MIA JEANS </title>
    <link rel="stylesheet" href="styles.css">
    <style>
        /* Estilo para el cuerpo de la página */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: rgb(245, 245, 245);
            color: #333;
            line-height: 1.6;
        }

        /* Estilo para el encabezado */
        header {
            background-color: #8722b3;
            /*color del encabezado*/
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        

        header h1 {
            margin: 0;
        }

        /* Estilo para la navegación */
        nav ul {
            list-style-type: none;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin-right: 15px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
        }

        /* Estilo para las secciones */
        section {
            padding: 20px;
            margin: 20px;
            border-radius: 8px;
        }

        /* Colores distintivos para cada sección */
        #inicio {
            background-color: #e0f7fa;
            /* Azul claro */
        }

        #biografia {
        }


        #habilidades {
            background-color: #c8e6c9;
            /* Verde claro */
        }
            

        #proyectos {
            background-color: #f8bbd0;
            /* Rosa claro */
        }

        #contacto {
            background-color: #d1c4e9;
            /* Morado claro */
        }

        /* Estilo para el pie de página */
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: relative;
            width: 100%;
            bottom: 0;
        }
        #habilidades {
    background-color: #f4f4f4;
    padding: 50px 0;
    text-align: center;
}

#habilidades h2 {
    font-size: 36px;
    color: #333;
    margin-bottom: 30px;
}

.habilidades-container {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
    gap: 20px;
}

.habilidad {
    background-color: #fff;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    padding: 20px;
    max-width: 300px;
    text-align: center;
}

.habilidad img {
    width: 100%;
    height: auto;
    border-radius: 8px;
}

.habilidad h3 {
    font-size: 24px;
    color: #007bff;
    margin-top: 20px;
}

.habilidad p {
    font-size: 16px;
    color: #555;
    margin-top: 10px;
}



    </style>
</head>

<body>
    <header>
        <h1>SHIRLEY MAYERLI APAZA QUISPE</h1>
        <nav>
            <ul>
                <li><a href="#inicio">Inicio</a></li>
                <li><a href="#biografia">Biografía</a></li>
                <li><a href="#habilidades">Habilidades</a></li>
                <li><a href="#proyectos">Proyectos</a></li>
                <li><a href="#contacto">Contacto</a></li>
            </ul>
        </nav>
    </header>

    <section id="inicio">
        <h2>Inicio</h2>
        <p>¡Hola! Soy [Tu Nombre], bienvenido a mi página personal donde puedes conocer más sobre mí, mis habilidades y
            mis proyectos.</p>
        <img src="logo.jfif" alt="Descripción de la imagen" class="header-image">

    </section>

    <section id="biografia">
        <h2>Biografía</h2>
        <p>[Aquí puedes escribir una breve biografía sobre ti. Incluye información sobre tu formación, experiencia y
            cualquier detalle que consideres relevante.]</p>
    </section>

    <section id="habilidades">
        <h2>Habilidades y Ventajas Competitivas</h2>
        <div class="habilidades-container">
            <div class="habilidad">
                <img src="https://images.pexels.com/photos/374132/pexels-photo-374132.jpeg" alt="Innovación en diseño de textiles">
                <h3>Innovación en el diseño</h3>
                <p>Desarrollo de productos textiles innovadores y creativos que siguen las tendencias globales.</p>
            </div>
            <div class="habilidad">
                <img src="https://images.pexels.com/photos/3826676/pexels-photo-3826676.jpeg" alt="Producción sostenible">
                <h3>Producción sostenible</h3>
                <p>Compromiso con el medio ambiente, utilizando materiales ecológicos y procesos responsables.</p>
            </div>
            <div class="habilidad">
                <img src="https://images.pexels.com/photos/373808/pexels-photo-373808.jpeg" alt="Control de calidad">
                <h3>Control de calidad</h3>
                <p>Garantizamos productos de alta calidad mediante procesos rigurosos de control.</p>
            </div>
            <div class="habilidad">
                <img src="https://images.pexels.com/photos/797626/pexels-photo-797626.jpeg" alt="Capacidad de producción en masa">
                <h3>Capacidad de producción en masa</h3>
                <p>Producción eficiente para cumplir con grandes volúmenes y tiempos de entrega ajustados.</p>
            </div>
            <div class="habilidad">
                <img src="https://images.pexels.com/photos/4210809/pexels-photo-4210809.jpeg" alt="Adaptabilidad a tendencias">
                <h3>Adaptabilidad y personalización</h3>
                <p>Flexibilidad para personalizar productos según las demandas y tendencias del mercado.</p>
            </div>
        </div>
    </section>
    
    

    <section id="proyectos">
        <h2>Proyectos</h2>
        <ul>
            <li>
                <strong>Proyecto 1:</strong> [Descripción breve del proyecto y tecnologías utilizadas.]
            </li>
            <li>
                <strong>Proyecto 2:</strong> [Descripción breve del proyecto y tecnologías utilizadas.]
            </li>
            <li>
                <strong>Proyecto 3:</strong> [Descripción breve del proyecto y tecnologías utilizadas.]
            </li>
            <!-- Añade más proyectos si es necesario -->
        </ul>
    </section>

    <section id="contacto">
        <h2>Contacto</h2>
        <p>Puedes contactarme a través de los siguientes medios:</p>
        <ul>
            <li>Correo: <a href="mailto:contacto@miempresa.com">contacto@miempresa.com</a></li>
            <li>Teléfono: +123 456 7890</li>
            <li>LinkedIn: <a href="https://www.linkedin.com/in/tu-perfil" target="_blank">Tu Perfil</a></li>
            <!-- Añade más formas de contacto si es necesario -->
        </ul>
    </section>

    <footer>
        <p>&copy; 2024 [Tu Nombre]. Todos los derechos reservados.</p>
    </footer>
</body>

</html>