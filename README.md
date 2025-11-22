<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>ST Emanuel - Servicio Técnico Profesional</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #0d1117; /* fondo oscuro elegante */
      color: #e6edf3;
    }
    header {
      background: linear-gradient(135deg, #004aad, #0a3d62, #001b44);
      padding: 40px;
      text-align: center;
      border-bottom: 4px solid #d4af37;
    }
    h1 { font-size: 40px; margin: 0; color: #d4af37; }
    h2 { font-size: 28px; color: #4ea8de; margin-bottom: 10px; text-align: center;}
    h3 { color: #d4af37; }

    /* Secciones */
    section {
      padding: 50px 20px;
      max-width: 1200px;
      margin: auto;
      border-bottom: 1px solid #1f2631;
    }

    /* Tabla de precios */
    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 20px;
    }
    th, td {
      padding: 14px;
      border: 1px solid #283347;
      text-align: left;
    }
    th {
      background-color: #004aad;
      color: #fff;
    }
    tr:hover { background-color: #1c2331; }

    /* Botones */
    .btn, .btn-whatsapp {
      padding: 12px 22px;
      font-size: 18px;
      display: inline-block;
      background-color: #004aad;
      color: #fff;
      border-radius: 8px;
      margin-top: 25px;
      text-decoration: none;
      transition: 0.3s;
    }
    .btn:hover, .btn-whatsapp:hover {
      background-color: #d4af37;
      color: #000;
    }

    /* Form */
    form input, form textarea {
      width: 100%; padding: 14px; margin-top: 10px; border-radius: 8px; border: none;
      background-color: #1c2331; color: #e6edf3;
    }

    .gallery-placeholder {
      width: 300px; height: 200px; border: 2px dashed #d4af37;
      display:flex; align-items:center; justify-content:center;
      margin:10px; background:#1b2230;
    }

    footer {
      background:#001b44; padding:30px; text-align:center; border-top:3px solid #d4af37;
    }
  </style>
</head>
<body>
  <header>
    <div style="display:flex; flex-direction:column; align-items:center; gap:12px;">
      <div style="width:90px; height:90px; border-radius:50%; border:3px solid #d4af37; display:flex; align-items:center; justify-content:center; font-size:32px; font-weight:bold; color:#d4af37; background:#001b44;">ST</div>
      <h1>ST Emanuel - Dios con nosotros</h1>
      <p style="font-size:20px; color:#fff;">Servicio Técnico Profesional en Celulares, Notebooks y Computadoras</p>
    </div>
  </header>

  <section>
    <h2>¿Quiénes Somos?</h2>
    <p>En <strong>ST Emanuel</strong> brindamos soluciones profesionales y confiables en reparación de equipos electrónicos. Nuestra prioridad es la transparencia, la calidad en los resultados y la atención personalizada. Con años de experiencia real, garantizamos diagnósticos honestos y reparaciones eficientes utilizando repuestos de calidad comprobada.</p>
  </section>

  <section>
    <h2>Servicios Especializados</h2>
    <ul>
      <li>Reparación de celulares, tablets, PC y notebooks</li>
      <li>Cambio de módulos y pantallas</li>
      <li>Cambio de pines de carga y conectores</li>
      <li>Software, liberaciones, desbloqueos, restauraciones</li>
      <li>Soldadura y reparación de placa madre</li>
      <li>Reemplazo de baterías</li>
      <li>Mantenimiento general y limpieza interna</li>
    </ul>
  </section>

  <section>
    <h2>Lista de Precios</h2>
    <table>
      <tr><th>Servicio</th><th>Precio</th></tr>
      <tr><td>Cambio pin de carga tipo V8</td><td>$25.000</td></tr>
      <tr><td>Cambio pin de carga tipo C</td><td>$30.000</td></tr>
      <tr><td>Eliminación de virus / malware móvil</td><td>$8.000 a $20.000 (según caso)</td></tr>
      <tr><td>Limpieza interna y mantenimiento de celular</td><td>$10.000</td></tr>
      <tr><td>Reemplazo de batería</td><td>Consultar</td></tr>
      <tr><td>Cambio de módulo o pantalla</td><td>Consultar por WhatsApp</td></tr>
      <tr><td>Diagnóstico y presupuesto</td><td>Sin costo*</td></tr>
      <tr><td>Recuperación de datos / memorias dañadas</td><td>Consultar</td></tr>
      <tr><td>Reparaciones microelectrónicas / placa madre</td><td>Consultar</td></tr>
      <tr><td>Formateo y optimización de PC / notebook</td><td>$18.000</td></tr>
    </table>

    <h3>Datos de pago</h3>
    <p><strong>Alias:</strong> ST.Emanuel</p>
    <p><strong>CBU:</strong> 0000184305010015499013</p>
  </section>

  

  <section>
    <h2>Contacto y Consultas</h2>
    <form action="https://formspree.io/f/mdkbeqjy" method="POST">
      <input type="text" name="name" placeholder="Tu nombre" required />
      <input type="email" name="email" placeholder="Tu correo" required />
      <textarea name="message" placeholder="Escribe tu consulta aquí..." rows="5" required></textarea>
      <input type="hidden" name="_subject" value="Nueva consulta desde ST Emanuel" />
      <input type="hidden" name="_autoresponse" value="Gracias por escribirnos. Tu consulta fue recibida correctamente y responderemos a la brevedad. ST Emanuel.">
      <button class="btn" type="submit">Enviar Consulta</button>
    </form>
    <a class="btn-whatsapp" href="https://wa.me/5492614857708?text=Hola%20ST%20Emanuel%2C%20necesito%20hacer%20una%20consulta%20sobre%20una%20reparaci%C3%B3n" target="_blank">WhatsApp Directo</a>
  </section>

  <section>
    <h2>Ubicación del Local</h2>
    <p>Haz clic en el botón para abrir directamente nuestra ubicación en Google Maps.</p>
    <a class="btn" href="https://maps.app.goo.gl/FCghJDdmtXqz9rQs8" target="_blank">📍 Ver ubicación en Google Maps</a>
  </section>

  <footer>
    <p>© 2025 ST Emanuel - Servicio Técnico Profesional</p>
    <p>Zona de cobertura: Zona Este - San Martín y Montecaseros</p>
  </footer>

</body>
</html>
