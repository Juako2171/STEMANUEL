<!DOCTYPE html>
<html lang="es">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />

  <title>ST Emanuel - Servicio Técnico Profesional</title>

  <meta name="description"
    content="Servicio técnico profesional en Montecaseros Tres Esquinas, San Martín Mendoza. Reparación de celulares, notebooks y PC.">

  <meta name="keywords"
    content="servicio técnico San Martín Mendoza, reparación celulares, notebooks, ST Emanuel">

  <link rel="stylesheet"
    href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

  <style>

    *{
      box-sizing:border-box;
    }

    body{
      margin:0;
      font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background:#0d1117;
      color:#e6edf3;
      line-height:1.6;
    }

    header{
      background:linear-gradient(135deg,#004aad,#0a3d62,#001b44);
      padding:50px 20px;
      text-align:center;
      border-bottom:4px solid #00d26a;
    }

    h1{
      font-size:clamp(32px,6vw,50px);
      margin:0;
      color:#ffffff;
    }

    h2{
      font-size:clamp(26px,5vw,34px);
      color:#4ea8de;
      text-align:center;
      margin-bottom:25px;
    }

    h3{
      color:#00ff88;
    }

    section{
      padding:60px 20px;
      max-width:1200px;
      margin:auto;
      border-bottom:1px solid #1f2631;

      animation:fadeIn .8s ease;
    }

    @keyframes fadeIn{
      from{
        opacity:0;
        transform:translateY(20px);
      }

      to{
        opacity:1;
        transform:translateY(0);
      }
    }

    ul li{
      margin-bottom:14px;
      font-size:17px;
    }

    table{
      width:100%;
      border-collapse:collapse;
      margin-top:25px;
    }

    th,td{
      padding:14px;
      border:1px solid #283347;
      text-align:left;
    }

    th{
      background:#004aad;
      color:#fff;
    }

    tr:hover{
      background:#1c2331;
    }

    .btn,
    .btn-whatsapp{

      padding:14px 24px;
      font-size:18px;

      display:inline-block;

      background:#004aad;

      color:#fff;

      border-radius:10px;

      margin-top:25px;

      text-decoration:none;

      transition:.3s;

      border:none;

      cursor:pointer;

      box-shadow:
      0 0 15px rgba(0,255,136,.25);
    }

    .btn:hover,
    .btn-whatsapp:hover{

      background:#00d26a;
      color:#000;

      transform:translateY(-2px);
    }

    form input,
    form textarea{

      width:100%;

      padding:14px;

      margin-top:12px;

      border:none;

      border-radius:8px;

      background:#1c2331;

      color:#fff;

      font-size:16px;
    }

    .benefits,
    .testimonials{

      display:grid;

      grid-template-columns:
      repeat(auto-fit,minmax(250px,1fr));

      gap:20px;

      margin-top:30px;
    }

    .benefit-box,
    blockquote{

      background:#161b22;

      padding:25px;

      border-radius:14px;

      border:1px solid #283347;

      transition:.3s;
    }

    .benefit-box:hover{
      transform:translateY(-5px);
      border-color:#00ff88;
    }

    blockquote{
      border-left:4px solid #00ff88;
    }

    footer{

      background:#001b44;

      padding:40px 20px;

      text-align:center;

      border-top:3px solid #00d26a;
    }

    /* =======================
       LOGO PROFESIONAL
    ======================= */

    .logo-real{

      display:flex;
      flex-direction:column;
      align-items:center;
      justify-content:center;

      background:
      linear-gradient(
      145deg,
      #02152f,
      #003b7a,
      #001b44
      );

      border:3px solid #00d26a;

      border-radius:22px;

      padding:24px 36px;

      box-shadow:
      0 0 18px rgba(0,210,106,.35),
      0 0 40px rgba(0,74,173,.30);

      max-width:430px;

      position:relative;

      overflow:hidden;
    }

    .logo-real::before{

      content:"";

      position:absolute;

      width:200%;
      height:200%;

      background:
      radial-gradient(
      rgba(255,255,255,.08),
      transparent 60%
      );

      top:-50%;
      left:-50%;

      animation:shine 6s linear infinite;
    }

    @keyframes shine{

      0%{
        transform:rotate(0deg);
      }

      100%{
        transform:rotate(360deg);
      }
    }

    .logo-icon{

      font-size:30px;

      color:#00ff88;

      margin-bottom:10px;

      text-shadow:
      0 0 12px rgba(0,255,136,.7);

      z-index:2;
    }

    .logo-main{

      font-size:72px;

      font-weight:900;

      letter-spacing:5px;

      color:#ffffff;

      line-height:1;

      z-index:2;

      text-shadow:
      0 0 8px rgba(255,255,255,.5),
      0 0 18px rgba(0,255,136,.7),
      0 0 35px rgba(0,74,173,.5);
    }

    .logo-sub{

      margin-top:10px;

      font-size:18px;

      font-weight:800;

      color:#00ff88;

      text-align:center;

      letter-spacing:1px;

      z-index:2;
    }

    .logo-mini{

      margin-top:6px;

      font-size:13px;

      color:#e6edf3;

      font-style:italic;

      z-index:2;
    }

    iframe{
      border-radius:14px;
      margin-top:25px;
    }

    @media(max-width:768px){

      .logo-main{
        font-size:50px;
      }

      .logo-sub{
        font-size:14px;
      }

      table{
        font-size:14px;
      }
    }

  </style>

</head>

<body>

<header>

  <div style="
    display:flex;
    flex-direction:column;
    align-items:center;
    gap:20px;
  ">

    <div class="logo-real">

      <div class="logo-icon">
        <i class="fa-solid fa-microchip"></i>
      </div>

      <div class="logo-main">
        STE
      </div>

      <div class="logo-mini">
        Dios con nosotros
      </div>

    </div>

    <p style="
      font-size:20px;
      color:#fff;
      max-width:750px;
      text-align:center;
    ">

      Servicio Técnico Profesional en Celulares,
      Notebooks y Computadoras

    </p>

  </div>

</header>

<section>

  <h2>¿Quiénes Somos?</h2>

  <p>

    En <strong>ST Emanuel</strong> brindamos soluciones profesionales y confiables
    en reparación de equipos electrónicos.

    Nuestra prioridad es la transparencia, la calidad y la atención personalizada.

  </p>

</section>

<section>

  <h2>Servicios Especializados</h2>

  <ul>

    <li><i class="fa-solid fa-mobile-screen"></i> Reparación de celulares y tablets</li>

    <li><i class="fa-solid fa-laptop"></i> Reparación de notebooks y computadoras</li>

    <li><i class="fa-solid fa-screwdriver-wrench"></i> Cambio de módulos y pantallas</li>

    <li><i class="fa-solid fa-bolt"></i> Cambio de pines de carga</li>

    <li><i class="fa-solid fa-microchip"></i> Reparaciones microelectrónicas</li>

    <li><i class="fa-solid fa-battery-full"></i> Cambio de baterías</li>

    <li><i class="fa-solid fa-shield-virus"></i> Eliminación de virus</li>

    <li><i class="fa-solid fa-soap"></i> Limpieza interna y mantenimiento</li>

  </ul>

</section>

<section>

  <h2>¿Por qué elegir ST Emanuel?</h2>

  <div class="benefits">

    <div class="benefit-box">

      <h3>✔ Diagnóstico Honesto</h3>

      <p>
        Evaluamos cada equipo con total transparencia.
      </p>

    </div>

    <div class="benefit-box">

      <h3>✔ Repuestos de Calidad</h3>

      <p>
        Utilizamos componentes confiables y garantizados.
      </p>

    </div>

    <div class="benefit-box">

      <h3>✔ Atención Personalizada</h3>

      <p>
        Seguimiento y asesoramiento claro para cada cliente.
      </p>

    </div>

  </div>

</section>

<section>

  <h2>Lista de Precios</h2>

  <table>

    <tr>
      <th>Servicio</th>
      <th>Precio</th>
    </tr>

    <tr>
      <td>Cambio pin de carga tipo V8</td>
      <td>$25.000</td>
    </tr>

    <tr>
      <td>Cambio pin de carga tipo C</td>
      <td>$30.000</td>
    </tr>

    <tr>
      <td>Eliminación de virus / malware móvil</td>
      <td>$8.000 a $20.000</td>
    </tr>

    <tr>
      <td>Limpieza interna y mantenimiento</td>
      <td>$10.000</td>
    </tr>

    <tr>
      <td>Cambio de batería (mano de obra)</td>
      <td>$15.000</td>
    </tr>

    <tr>
      <td>Cambio de módulo o pantalla</td>
      <td>Depende del modelo</td>
    </tr>

    <tr>
      <td>Diagnóstico y presupuesto</td>
      <td>Sin costo*</td>
    </tr>

    <tr>
      <td>Recuperación de datos</td>
      <td>Consultar</td>
    </tr>

    <tr>
      <td>Microelectrónica / placa madre</td>
      <td>Consultar</td>
    </tr>

    <tr>
      <td>Formateo y optimización PC / notebook</td>
      <td>$18.000</td>
    </tr>

  </table>

  <h3>Datos de pago</h3>

  <p><strong>Alias:</strong> ST.Emanuel</p>

  <p><strong>CBU:</strong> 0000184305010015499013</p>

</section>

<section>

  <h2>Opiniones de Clientes</h2>

  <div class="testimonials">

    <blockquote>
      “Excelente atención y rapidez. Mi celular quedó como nuevo.”
    </blockquote>

    <blockquote>
      “Muy recomendable, honestidad y buen precio.”
    </blockquote>

    <blockquote>
      “Atención responsable y trabajos de calidad.”
    </blockquote>

  </div>

</section>

<section>

  <h2>Contacto y Consultas</h2>

  <form action="https://formspree.io/f/mdkbeqjy" method="POST">

    <input type="text"
      name="name"
      placeholder="Tu nombre"
      required />

    <input type="email"
      name="email"
      placeholder="Tu correo"
      required />

    <textarea
      name="message"
      rows="5"
      placeholder="Escribe tu consulta aquí..."
      required></textarea>

    <button class="btn" type="submit">

      Enviar Consulta

    </button>

  </form>

  <br>

  <a class="btn-whatsapp"

    href="https://wa.me/5492614857708?text=Hola%20ST%20Emanuel%20necesito%20hacer%20una%20consulta"

    target="_blank"

    rel="noopener noreferrer">

    <i class="fa-brands fa-whatsapp"></i>

    WhatsApp Directo

  </a>

</section>

<section>

  <h2>Ubicación del Local</h2>

  <p>

    📍 Nos encontramos en
    <strong>Montecaseros Tres Esquinas, San Martín, Mendoza</strong>,
    cerca de la
    <strong>Escuela Primaria Patria 1-161</strong>.

  </p>

  <a class="btn"

    href="https://maps.app.goo.gl/FCghJDdmtXqz9rQs8"

    target="_blank"

    rel="noopener noreferrer">

    📍 Ver ubicación en Google Maps

  </a>

</section>

<footer>

  <p>
    © 2026 ST Emanuel - Servicio Técnico Profesional
  </p>

  <p>
    Zona de cobertura:
    Montecaseros Tres Esquinas,
    San Martín y Zona Este
  </p>

</footer>

</body>
</html>
