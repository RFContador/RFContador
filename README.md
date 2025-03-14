<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contador Profesional</title>
    <style>
        body { 
            font-family: Arial, sans-serif; 
            margin: 0; 
            padding: 0; 
            color: #333;
            background: url('https://source.unsplash.com/1600x900/?finance,accounting') no-repeat center center fixed;
            background-size: cover;
        }
        header { 
            background: rgba(26, 26, 46, 0.9); 
            color: white; 
            padding: 20px; 
            text-align: center; 
        }
        nav { 
            background: rgba(22, 33, 62, 0.9); 
            padding: 15px; 
            text-align: center; 
        }
        nav a { 
            color: white; 
            margin: 0 15px; 
            text-decoration: none; 
            font-weight: bold; 
        }
        section { 
            padding: 60px; 
            text-align: center;
            background: rgba(255, 255, 255, 0.9);
            margin: 20px;
            border-radius: 10px;
        }
        footer { 
            background: rgba(26, 26, 46, 0.9); 
            color: white; 
            text-align: center; 
            padding: 15px; 
            width: 100%;
        }
        form { 
            max-width: 400px; 
            margin: auto; 
            text-align: left; 
        }
        input, textarea { 
            width: 100%; 
            padding: 10px; 
            margin: 5px 0; 
            border-radius: 5px;
            border: 1px solid #ccc;
        }
        button { 
            background: #16213e; 
            color: white; 
            padding: 10px; 
            border: none; 
            cursor: pointer; 
            width: 100%; 
            border-radius: 5px;
            font-size: 16px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Contador Profesional</h1>
    </header>
    <nav>
        <a href="#inicio">Inicio</a>
        <a href="#sobre-mi">Sobre Mí</a>
        <a href="#servicios">Servicios</a>
        <a href="#contacto">Contacto</a>
    </nav>
    <section id="inicio">
        <h2>Bienvenido</h2>
        <p>Evita errores y multas por falta de información, deja tu contabilidad en manos expertas.</p>
    </section>
    <section id="sobre-mi">
        <h2>Sobre Mí</h2>
        <p>Contador dedicado a brindar soluciones contables integrales a personas y empresas. Mi enfoque va más allá de los números, ofrezco un servicio cercano, personalizado y eficiente, asegurando que cada cliente cumpla con sus obligaciones tributarias de manera ordenada y sin complicaciones.</p>
        <p>Cuento con amplia experiencia en:</p>
        <ul>
            <li>Operación Renta</li>
            <li>Pago de impuestos mensuales</li>
            <li>Remuneraciones</li>
            <li>Pagos previsionales</li>
            <li>Acuerdos con Tesorería</li>
            <li>Balances y análisis</li>
            <li>Conciliaciones bancarias</li>
        </ul>
        <p>Además, tengo un gran enfoque en Recursos Humanos, ayudando a empresas a optimizar su gestión laboral.</p>
        <p>Mi compromiso es ofrecer un servicio contable confiable, adaptado a las necesidades de cada cliente.</p>
    </section>
    <section id="servicios">
        <h2>Servicios</h2>
        <ul>
            <li>Pago de impuestos mensuales</li>
            <li>Pago de nómina de remuneraciones</li>
            <li>Pagos previsionales</li>
            <li>Acuerdos con Tesorería</li>
            <li>Quiebras</li>
            <li>Operación Renta</li>
            <li>Balances y análisis</li>
            <li>Conciliaciones bancarias</li>
        </ul>
    </section>
    <section id="contacto">
        <h2>Contacto</h2>
        <p>Email: rfariascontador@gmail.com</p>
        <p>Teléfono: +56942110441</p>
        <form>
            <label>Nombre:</label>
            <input type="text" required>
            <label>Email:</label>
            <input type="email" required>
            <label>Mensaje:</label>
            <textarea rows="4" required></textarea>
            <button type="submit">Enviar</button>
        </form>
    </section>
    <footer>
        <p>&copy; 2025 Contador Profesional</p>
    </footer>
</body>
</html>
