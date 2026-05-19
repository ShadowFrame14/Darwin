<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Catálogo de Entretenimiento Digital</title>
    <style>
        @page {
            size: A4;
            margin: 15mm 12mm;
            background-color: #ffffff;
        }
        
        *, *::before, *::after {
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Arial, sans-serif;
            color: #2c3e50;
            margin: 0;
            padding: 0;
            background-color: #ffffff;
            font-size: 10.5pt;
            line-height: 1.4;
        }

        .header-banner {
            background: linear-gradient(135deg, #1e1e2f, #3a3a52);
            color: #ffffff;
            padding: 25px 20px;
            text-align: center;
            border-radius: 6px;
            margin-bottom: 25px;
        }

        .header-banner h1 {
            margin: 0;
            font-size: 20pt;
            font-weight: bold;
            letter-spacing: 0.5px;
        }

        .header-banner p {
            margin: 8px 0 0 0;
            font-size: 11pt;
            color: #b0b0cd;
        }

        h2 {
            font-size: 14pt;
            color: #1e1e2f;
            border-left: 4px solid #e91e63;
            padding-left: 10px;
            margin-top: 30px;
            margin-bottom: 15px;
            page-break-after: avoid;
        }

        p {
            margin: 0 0 12px 0;
        }

        .intro-box {
            background-color: #f8f9fa;
            border: 1px solid #e9ecef;
            padding: 15px;
            border-radius: 6px;
            margin-bottom: 25px;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 15px;
            margin-bottom: 25px;
        }

        th {
            background-color: #2c3e50;
            color: #ffffff;
            font-weight: bold;
            text-align: left;
            padding: 10px 12px;
            font-size: 10pt;
            border: 1px solid #2c3e50;
        }

        td {
            padding: 10px 12px;
            border: 1px solid #dee2e6;
            font-size: 10pt;
            vertical-align: middle;
        }

        tr:nth-child(even) {
            background-color: #fdfdfd;
        }

        .platform-name {
            font-weight: bold;
            color: #e91e63;
        }

        .price {
            font-weight: bold;
            color: #2e7d32;
        }

        .badge-screen {
            background-color: #e3f2fd;
            color: #0d47a1;
            padding: 2px 6px;
            border-radius: 4px;
            font-size: 8.5pt;
            font-weight: bold;
        }

        .badge-full {
            background-color: #f3e5f5;
            color: #4a148c;
            padding: 2px 6px;
            border-radius: 4px;
            font-size: 8.5pt;
            font-weight: bold;
        }

        .code-container {
            background-color: #1e1e1e;
            color: #d4d4d4;
            padding: 15px;
            border-radius: 6px;
            font-family: 'Courier New', Courier, monospace;
            font-size: 9pt;
            white-space: pre-wrap;
            margin-top: 15px;
            margin-bottom: 25px;
            border: 1px solid #333333;
        }

        .instruction-list {
            margin: 0 0 20px 0;
            padding-left: 20px;
        }

        .instruction-list li {
            margin-bottom: 8px;
        }

        .whatsapp-btn-demo {
            display: inline-block;
            background-color: #25d366;
            color: white;
            padding: 6px 12px;
            border-radius: 4px;
            text-decoration: none;
            font-size: 9pt;
            font-weight: bold;
        }
    </style>
</head>
<body>

    <div class="header-banner">
        <h1>Estructura Digital: Venta de Streaming</h1>
        <p>Proyectos G — Documentación de Código y Despliegue Local en COP</p>
    </div>

    <div class="intro-box">
        <p><strong>Nota del Proyecto:</strong> Esta propuesta está diseñada para apoyar el negocio de tu mamá aprovechando el tráfico orgánico o directo que ella ya maneja. Consiste en una página web limpia, rápida y optimizada para dispositivos móviles, donde los clientes pueden ver los precios en <strong>Pesos Colombianos (COP)</strong> y enviar un pedido automático directamente a su <strong>WhatsApp</strong> con un solo clic.</p>
    </div>

    <h2>1. Lista de Precios Sugerida (Formato del Catálogo)</h2>
    <p>A continuación se detalla la estructura de datos que alimenta el código interactivo. Los precios están adaptados al mercado común local:</p>

    <table>
        <thead>
            <tr>
                <th>Plataforma</th>
                <th>Tipo de Servicio</th>
                <th>Precio Mensual (COP)</th>
                <th>Beneficios Incluidos</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td class="platform-name">Netflix</td>
                <td><span class="badge-screen">1 Pantalla</span></td>
                <td class="price">$12.000</td>
                <td>Ultra HD, cuenta compartida estable, perfil personalizado.</td>
            </tr>
            <tr>
                <td class="platform-name">Netflix</td>
                <td><span class="badge-full">Cuenta Completa</span></td>
                <td class="price">$44.000</td>
                <td>4 Pantallas simultáneas originales, sin caídas.</td>
            </tr>
            <tr>
                <td class="platform-name">Disney+</td>
                <td><span class="badge-screen">1 Pantalla</span></td>
                <td class="price">$10.000</td>
                <td>Catálogo completo (incluye Star), audio premium.</td>
            </tr>
            <tr>
                <td class="platform-name">Crunchyroll</td>
                <td><span class="badge-full">Cuenta Completa</span></td>
                <td class="price">$9.000</td>
                <td>Mega Fan, sin publicidad, visualización sin conexión.</td>
            </tr>
            <tr>
                <td class="platform-name">Max (HBO)</td>
                <td><span class="badge-screen">1 Pantalla</span></td>
                <td class="price">$8.000</td>
                <td>Contenido exclusivo de Warner Bros y Discovery.</td>
            </tr>
            <tr>
                <td class="platform-name">Paramount+</td>
                <td><span class="badge-full">Cuenta Completa</span></td>
                <td class="price">$7.000</td>
                <td>Todo el catálogo de canales premium y deportes.</td>
            </tr>
        </tbody>
    </table>

    <h2>2. Código Fuente HTML y JavaScript (Listo para usar)</h2>
    <p>Este código lo puedes guardar en tu computadora con el nombre <code>index.html</code>. No requiere servidores costosos y funciona de inmediato en cualquier celular o computador:</p>

    <div class="code-container">&lt;!DOCTYPE html&gt;
&lt;html lang="es"&gt;
&lt;head&gt;
    &lt;meta charset="UTF-8"&gt;
    &lt;meta name="viewport" content="width=device-width, initial-scale=1.0"&gt;
    &lt;title&gt;Streaming Premium Colombia&lt;/title&gt;
    &lt;style&gt;
        body { font-family: sans-serif; background: #121214; color: #fff; text-align: center; padding: 20px; }
        .grid { display: block; max-width: 500px; margin: 0 auto; }
        .card { background: #202024; border-radius: 8px; padding: 15px; margin-bottom: 15px; border: 1px solid #29292e; text-align: left; }
        .title { font-size: 18px; font-weight: bold; color: #e91e63; }
        .price { color: #00b574; font-size: 16px; font-weight: bold; margin: 5px 0; }
        .btn { display: block; background: #25d366; color: #fff; text-align: center; padding: 10px; border-radius: 5px; text-decoration: none; font-weight: bold; margin-top: 10px; }
    &lt;/style&gt;
&lt;/head&gt;
&lt;body&gt;
    &lt;h1&gt;Plataformas de Entretenimiento&lt;/h1&gt;
    &lt;p&gt;Selecciona tu pantalla favorita y recíbela al instante por WhatsApp&lt;/p&gt;
    
    &lt;div class="grid"&gt;
        &lt;!-- Tarjeta de ejemplo: Cambiar el número 573000000000 por el real --&gt;
        &lt;div class="card"&gt;
            &lt;div class="title"&gt;Netflix - 1 Pantalla Premium&lt;/div&gt;
            &lt;div class="price"&gt;$12.000 COP / Mes&lt;/div&gt;
            &lt;p&gt;Garantía completa del mes, Ultra HD.&lt;/p&gt;
            &lt;a class="btn" href="https://wa.me/573000000000?text=Hola,%20quiero%20comprar%201%20pantalla%20de%20Netflix%20por%20$12.000%20COP" target="_blank"&gt;Pedir por WhatsApp&lt;/a&gt;
        &lt;/div&gt;

        &lt;div class="card"&gt;
            &lt;div class="title"&gt;Disney+ - 1 Pantalla Premium&lt;/div&gt;
            &lt;div class="price"&gt;$10.000 COP / Mes&lt;/div&gt;
            &lt;p&gt;Acceso a todas las series y películas.&lt;/p&gt;
            &lt;a class="btn" href="https://wa.me/573000000000?text=Hola,%20quiero%20comprar%201%20pantalla%20de%20Disney%20por%20$10.000%20COP" target="_blank"&gt;Pedir por WhatsApp&lt;/a&gt;
        &lt;/div&gt;
    &lt;/div&gt;
&lt;/body&gt;
&lt;/html&gt;</div>

    <h2>3. Instrucciones de Implementación Técnica</h2>
    <ol class="instruction-list">
        <li><strong>Configuración del Teléfono:</strong> Abre el código anterior y busca el fragmento <code>wa.me/573000000000</code>. Reemplaza los ceros por el número de WhatsApp de tu mamá (manteniendo el <code>57</code> de Colombia adelante sin el signo +).</li>
        <li><strong>Personalización de Mensajes:</strong> Puedes alterar el texto que sigue a <code>?text=</code> para que tu mamá sepa exactamente qué plataforma quiere el cliente apenas le llegue el mensaje.</li>
        <li><strong>Despliegue Gratuito:</strong> Sube este archivo a plataformas como <em>GitHub Pages</em> o <em>Vercel</em> de manera 100% gratuita para obtener un enlace público que ella pueda compartir en sus estados.</li>
    </ol>

    <h2>4. Propuesta de Proyecto Gratis para tu Salón de Clases</h2>
    <p>Como mencionaste que los grandes proyectos inician con algo pequeño y gratuito para tu salón, aquí tienes dos ideas que podemos programar directamente en este chat:</p>
    <ul>
        <li><strong>Gestor de Tareas y Fechas de Exámenes Común:</strong> Una mini aplicación web donde los delegados del salón suben los trabajos pendientes de filosofía, trigonometría, etc., y todos pueden consultarlos en tiempo real desde el celular sin perderse en los grupos de WhatsApp.</li>
        <li><strong>Calculadora Escolar de Notas de Periodo:</strong> Un sistema digital simple donde cada compañero ingresa sus notas acumuladas y la app le calcula automáticamente cuánto necesita sacar en el examen final para pasar la materia.</li>
    </ul>

</body>
</html>
