<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KSE Invitaciones</title>
    
    <!-- Estilos Consolidados -->
    <style>
      /* Fondo con imagen */
      body {
        background: url('imagenes/fondolila.jpg') no-repeat center center fixed;
        background-size: cover;
        font-family: Arial, sans-serif;
        font-size: 100;
        background-color: rgba(148, 74, 245, 0.747);
        margin: 0;
        padding: 0;
        text-align: center;
        color: #000;
      }
      
      /* Encabezado */
      header {  
        background: rgba(255, 255, 255, 0.8);
        padding: 90px;
      }
      header h2 {
        margin: 0;
      }
      nav ul {
        list-style: none;
        padding: 0;
        margin: 5px 0;
      }
      nav ul li {
        display: inline-block;
        margin: 0 10px;
      }
      nav ul li a {
        text-decoration: none;
        color: #000000;
      }
      
      /* Sección Spotify */
      section.spotify {
        margin: 20px auto;
        max-width: 600px;
      }
      
      /* Productos y Carrito */
      .producto {
        background: rgba(255, 255, 255, 0.9);
        margin: 10px;
        padding: 10px;
        border: 1px solid #ddd;
        display: inline-block;
        vertical-align: top;
      }
      .carrito, .form-pago {
        background: rgba(255, 255, 255, 0.9);
        margin: 20px auto;
        padding: 10px;
        border: 2px solid #333;
        width: 300px;
      }
      .carrito ul {
        list-style: none;
        padding: 0;
      }
      button {
        cursor: pointer;
        padding: 5px 10px;
        margin: 5px;
      }
      
      /* Secciones Generales */
      section {
        background: rgba(255, 255, 255, 0.85);
        margin: 20px auto;
        padding: 20px;
        max-width: 800px;
        border-radius: 8px;
      }
      
      table {
        width: 100%;
        border-collapse: collapse;
      }
      table, th, td {
        border: 1px solid #000000;
      }
      th, td {
        padding: 8px;
        text-align: center;
      }
      
      /* Formularios */
      form input, form textarea, form button {
        display: block;
        margin: 10px auto;
        width:80%;
        max-width: 400px;
        padding: 8px;
      }
      
      /* Galería */
      .galeria img {
        margin: 5px;
        border: 1px solid #ccc;
      }
      
      /* Footer */
      footer {
        background: rgba(255, 255, 255, 0.8);
        padding: 10px;
      }
    </style>
    
    <link rel="stylesheet" href="styles.css">
    <link rel="icon" href="favicon.ico" type="image/x-icon">
  </head>
  <body>
    <!-- Encabezado de la tienda -->
    <header>
      <h2>Bienvenidos a KSE INVITACIONES</h2>
      <nav>
        <ul>
          <li><a href="#productos">Productos</a></li>
          <li><a href="#nosotros">Nosotros</a></li>
          <li><a href="#contacto">Contacto</a></li>
        </ul>
      </nav>
      <p style="text-align: center;">
        ¡Bienvenidos a KSE_Invitaciones! Tu tienda online para encontrar invitaciones, horarios, calendarios personalizados y mucho más. 
        Disponibles en formatos digitales y físicos para hacer que cada celebración sea única y especial.
      </p>
    </header>
    <!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Banners Emergentes</title>
  <style>
    .banner {
      position: fixed;
      width: 300px;
      height: 250px;
      background-color: #ac4efe; /* Cambia este color */
      border: 1px solid #ccc;
      padding: 10px;
      box-shadow: 0 0 10px rgba(255, 255, 255, 0.2);
      z-index: 9999;
    }

    .banner.izquierda {
      bottom: 20px;
      left: 20px;
    }

    .banner.derecha {
      bottom: 20px;
      right: 20px;
    }

    .banner .cerrar {
      position: absolute;
      top: 5px;
      right: 8px;
      font-size: 20px;
      color: #000000;
      cursor: pointer;
    }

    .banner a {
      display: block;
      text-align: center;
      text-decoration: none;
      color: black;
    }

    .banner img {
      width: 90px;
      height: 100px;
      margin: 20px auto;
      display: block;
    }

    .banner p {
      margin-top: 10px;
      font-weight: bold;
    }
  </style>
</head>
<body>

  <!-- Banner Izquierdo -->
  <div class="banner izquierda" id="bannerIzq">
    <span class="cerrar" onclick="document.getElementById('bannerIzq').style.display='none'">×</span>
      <img src="imagenes/Invitaciones.jpg" alt="Promo izquierda">
      <p>¡Mira Las Promociones De Los Viernes!</p>
    </a>
  </div>

  <!-- Banner Derecho -->
  <div class="banner derecha" id="bannerDer">
    <span class="cerrar" onclick="document.getElementById('bannerDer').style.display='none'">×</span>
      <img src="imagenes/Separador De Libro.jpg" alt="Promo derecha">
      <p>¡Consulta Promociones De Fin De Cursos!</p>
    </a>
  </div>

    <!-- Sección Spotify -->
    <section class="spotify">
      <iframe style="border-radius:12px" src="https://open.spotify.com/embed/track/3AEZUABDXNtecAOSC1qTfo?utm_source=generator" width="100%" height="100" frameBorder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>
      <p>Cada Evento Comienza Con Un Gran Diseño</p>
      <script>
        // Funciones de audio (si se implementa un reproductor en el futuro)
        let audio = document.getElementById("audio-player");
        function reproducir() {
          if(audio) audio.play();
        }
        function pausar() {
          if(audio) audio.pause();
        }
      </script>
    </section>

    <!-- Sección de Productos -->
    <section id="productos">
     <h1>Productos</h1>
     <div class="producto">
       <h3>Invitación Personalizada - $45</h3>
       <button onclick="agregarAlCarrito('Invitación Personalizada', 45)">Añadir al Carrito</button>
     </div>
     <div class="producto">
       <h3>Separador de Libro - $50</h3>
       <button onclick="agregarAlCarrito('Separador De Libro Personalizado', 50)">Añadir al Carrito</button>
     </div>
     <div class="producto">
       <h3>Etiqueta Escolar - $25</h3>
       <button onclick="agregarAlCarrito('Etiqueta Escolar Personalizada', 25)">Añadir al Carrito</button>
     </div>
     <div class="producto">
       <h3>Diseño Para Playera Personalizado - $30</h3>
       <button onclick="agregarAlCarrito('Diseño Para Playera Personalizado', 30)">Añadir al Carrito</button>
     </div>
     <div class="producto">
       <h3>Bandera Decorativa Personalizada - $70</h3>
       <button onclick="agregarAlCarrito('Bandera Decorativa Personalizada', 70)">Añadir al Carrito</button>
     </div>
     <div class="producto">
       <h3>Etiquetas, Logos Y Tickets Personalizados - $30</h3>
       <button onclick="agregarAlCarrito('Etiquetas, Logos Y Tickets Personalizados', 30)">Añadir al Carrito</button>
     </div>
     <div class="producto">
       <h3>Horario Escolar Personalizado - $35</h3>
       <button onclick="agregarAlCarrito('Horario Escolar Personalizado', 35)">Añadir al Carrito</button>
     </div>
     <div class="producto">
       <h3>Calendario Personalizado - $50</h3>
       <button onclick="agregarAlCarrito('Calendario Personalizado', 50)">Añadir al Carrito</button>
     </div>
   </section>
 
     <h2>🛒 Carrito de Compras</h2>
     <div class="carrito">
         <ul id="lista-carrito"></ul>
         <p>Total: $<span id="total">0</span></p>
         <button onclick="mostrarFormularioPago()">🛍️ Proceder al Pago</button>
     </div>
 
     <div class="form-pago" id="form-pago">
         <h2>💳 Método de Pago</h2>
         <label>
             <input type="radio" name="metodoPago" value="tarjeta" checked> Tarjeta de Crédito
         </label>
         <br>
         <label>
             <input type="radio" name="metodoPago" value="paypal"> PayPal
         </label>
         <br><br>
         <label>
        <input type="radio" name="metodoPago" value="tranferencia"> Transferencia
        </label>
         <br><br>

         <div id="pago-tarjeta">
             <input type="text" id="nombre" placeholder="Nombre en la Tarjeta"><br><br>
             <input type="text" id="numTarjeta" placeholder="Número de Tarjeta"><br><br>
             <input type="text" id="exp" placeholder="Fecha Expiración (MM/AA)"><br><br>
             <input type="text" id="cvv" placeholder="CVV"><br><br>
         </div>
 
         <button onclick="realizarPago()">✅ Finalizar Compra</button>
     </div>
 
     <script>
         let carrito = []; 
         let total = 235;
 
         function agregarAlCarrito(nombre, precio) {
             carrito.push({ nombre, precio });
             total += precio;
             actualizarCarrito();
         }
 
         function actualizarCarrito() {
             let listaCarrito = document.getElementById("lista-carrito");
             let totalElemento = document.getElementById("total");
             listaCarrito.innerHTML = "";
             carrito.forEach((item, index) => {
                 let li = document.createElement("li");
                 li.textContent = `${item.nombre} - $${item.precio}`;
                 let botonEliminar = document.createElement("button");
                 botonEliminar.textContent = "❌";
                 botonEliminar.onclick = () => eliminarProducto(index);
                 li.appendChild(botonEliminar);
                 listaCarrito.appendChild(li);
             });
             totalElemento.textContent = total;
         }
 
         function eliminarProducto(index) {
             total -= carrito[index].precio;
             carrito.splice(index, 1);
             actualizarCarrito();
         }
 
         function mostrarFormularioPago() {
             if (carrito.length === 0) {
                 alert("❌ El carrito está vacío. Agrega productos antes de pagar.");
                 return;
             }
             document.getElementById("form-pago").style.display = "block";
         }
 
         function realizarPago() {
             let metodoPago = document.querySelector('input[name="metodoPago"]:checked').value;
 
             if (metodoPago === "tarjeta") {
                 let nombre = document.getElementById("nombre").value;
                 let numTarjeta = document.getElementById("numTarjeta").value;
                 let exp = document.getElementById("exp").value;
                 let cvv = document.getElementById("cvv").value;
 
                 if (!nombre || !numTarjeta || !exp || !cvv) {
                     alert("❌ Por favor, completa todos los datos de la tarjeta.");
                     return;
                 }
 
                 alert(`✅ Pago realizado con éxito.\nTotal pagado: $${total}\nMétodo: Tarjeta de Crédito`);
             } else {
                 alert(`✅ Redirigiendo a PayPal...\nTotal a pagar: $${total}`);
             }
 
             // Vaciar carrito después de la compra
             carrito = [];
             total = 0;
             actualizarCarrito();
             document.getElementById("form-pago").style.display = "none";
         }
         
     </script>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ticket de Compra Dinámico</title>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.5.1/jspdf.umd.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/qrcodejs/qrcode.min.js"></script>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
    }
    #ticket {
      width: 300px;
      margin: auto;
      padding: 15px;
      border: 1px solid #ccc;
      text-align: left;
    }
  </style>
</head>
<body>

  <h2>✅ Compra Realizada</h2>
  <div id="ticket">
    <h3>KSE INVITACIONES</h3>
    <p><em>"Cada evento comienza con un gran diseño"</em></p>
    <p id="fecha"></p>
    <p id="hora"></p>
    <p id="total"></p>
    <p id="productos"></p>
    <p><strong><Total:235></Total:235></strong> <span id="Total">Total:$235</span></p>
  </div>

  <br>
  <button onclick="generarPDF()">Descargar Ticket PDF</button>
  <div id="qrcode"></div>

  <script>
    // Simulamos un carrito almacenado en localStorage o backend
    const Carrito = JSON.parse(localStorage.getItem("carrito")) || [
    ];

    const Total = carrito.reduce((sum, p) => sum + p.precio, 0);

    document.getElementById("total").textContent = total.toFixed(2);
    const lista = document.getElementById("productos");
    carrito.forEach(p => {
      const li = document.createElement("li");
      li.textContent = `${p.nombre} - $${p.precio}`;
      lista.appendChild(li);
    });

    const hoy = new Date();
    document.getElementById("fecha").textContent = `Fecha: ${hoy.toLocaleDateString()}`;
    document.getElementById("hora").textContent = `Hora: ${hoy.toLocaleTimeString()}`;

    function generarPDF() {
      const { jsPDF } = window.jspdf;
      const doc = new jsPDF();
      let y = 10;
      doc.text("KSE INVITACIONES", 10, y); y += 7;
      doc.text("\"Cada evento comienza con un gran diseño\"", 10, y); y += 10;
      doc.text(`Fecha: ${hoy.toLocaleDateString()}`, 10, y); y += 7;
      doc.text(`Hora: ${hoy.toLocaleTimeString()}`, 10, y); y += 7;
      doc.text("Productos:", 10, y); y += 7;
      carrito.forEach(p => {
        doc.text(`- ${p.nombre}: $${p.precio}`, 12, y); y += 7;
      });
      doc.text(`Total: $${total.toFixed(2)}`, 10, y);
      doc.save("Ticket_KSE_Compra.pdf");
    }

    new QRCode(document.getElementById("qrcode"), {
      text: `Compra KSE - Total: $${total.toFixed(2)} - Fecha: ${hoy.toLocaleDateString()} ${hoy.toLocaleTimeString()}`,
      width: 128,
      height: 128,
      colorDark : "#000000",
      colorLight : "#ffffff",
      correctLevel : QRCode.CorrectLevel.H
    });
  </script>
 
 </body>
 </html> 
    <!-- Sección de Información de la Tienda -->
    <main>
      <section id="nosotros">
        <h2>Nosotros</h2>
        <p style="text-align: justify;">
          La historia de KSE Invitaciones nace de la pasión por el diseño y la creatividad. 
          Ofrecemos invitaciones y productos personalizados que reflejan el estilo único de cada cliente. 
          Nuestro compromiso es hacer que cada evento sea especial.
        </p>
      </section>
      
      <section id="detalles">
        <h2>Misión y Visión</h2>
        <blockquote>
            <p style="text-align: justify;">
          La misión de KSE Invitaciones es ofrecer productos de papelería personalizados que reflejen la esencia única de cada cliente, creando momentos memorables.
        </blockquote>
        <p style="text-align: justify;">
        <blockquote>
          La visión de KSE Invitaciones es ser líderes en el mercado de invitaciones personalizadas, destacando por nuestra creatividad e innovación.
        </blockquote>
      </section>
      
      <!-- Sección de Productos Detallados -->
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>KSE Invitaciones - Carrito</title>
  <script type="text/javascript" src="carrito_completo.js"></script>
</head>
<body>

  <div id="form-pago" style="display:none;">
    <h2>💳 Método de Pago</h2>
    <label><input type="radio" name="metodoPago" value="tarjeta" checked> Tarjeta de Crédito</label><br>
    <label><input type="radio" name="metodoPago" value="paypal"> PayPal</label><br>
    <label><input type="radio" name="metodoPago" value="transferencia"> Transferencia</label><br><br>

    <div id="pago-tarjeta">
      <input type="text" id="nombre" placeholder="Nombre en la Tarjeta"><br><br>
      <input type="text" id="numTarjeta" placeholder="Número de Tarjeta"><br><br>
      <input type="text" id="exp" placeholder="Fecha Expiración (MM/AA)"><br><br>
      <input type="text" id="cvv" placeholder="CVV"><br><br>
    </div>

    <button onclick="realizarPago()">✅ Finalizar Compra</button>
  </div>
</body>
</html>

        </table>
      </section>
      
      <!-- Galería de Productos -->
      <section class="galeria">
        <h2>Galería de Productos</h2>
        <img src="imagenes/Etiqueta Escolar.jpg" alt="Etiqueta Escolar Personalizada" width="200">
        <img src="imagenes/Horario Escolar.jpg" alt="Horario Escolar Personalizado" width="200">
        <img src="imagenes/Calendario Escolar.jpg" alt="Calendario Escolar Personalizado" width="200">
        <img src="imagenes/Bandera Decorativa.jpg" alt="Bandera Decorativa Personalizado" width="200">
        <img src="imagenes/Diseño Para Playera.jpg" alt="Diseño Personalizado Para Playera" width="200">
        <img src="imagenes/Etiquetas Y Logos.jpg" alt="Etiquetas Y Logos" width="200">
        <img src="imagenes/Separador De Libro.jpg" alt="Separador De Libro" width="200">
        <img src="imagenes/Invitaciones.jpg" alt="Invitaciones Personalizadas" width="200">
      </section>
      
      <!-- Términos y Condiciones -->
      <section>
        <h2>Términos y Condiciones</h2>
        <p style="text-align: justify;">
          Todos los diseños y especificaciones están sujetos a cambios sin previo aviso. 
          Todas las compras requieren aprobación. Las cotizaciones se basan en la información disponible al momento de la compra y no se aceptan devoluciones.
        </p>
      </section>
      
      <!-- Formulario de Contacto -->
      <!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Formulario de Contacto</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      padding: 20px;
    }

    form {
      max-width: 400px;
      margin: auto;
    }

    label {
      display: block;
      margin-top: 10px;
    }

    input, textarea {
      width: 100%;
      padding: 8px;
      margin-top: 5px;
      border-radius: 4px;
      border: 1px solid #ccc;
    }

    button {
      margin-top: 15px;
      padding: 10px 20px;
      background-color: #000000;
      color: white;
      border: none;
      border-radius: 4px;
      cursor: pointer;
    }

    button:hover {
      background-color: #45a049;
    }
  </style>
</head>
<body>

  <h2>Contáctanos</h2>
<form action="https://formsubmit.co/ksuarezestrada@gmail.com" method="POST">
    <label for="nombre">Nombre:</label>
    <input type="text" id="nombre" name="Nombre" required>

    <label for="apellido">Apellido:</label>
    <input type="text" id="apellido" name="Apellido" required>

    <label for="mensaje">Mensaje:</label>
    <textarea id="mensaje" name="Mensaje" rows="5" required></textarea> 

    <button type="submit">Enviar</button>
  </form>
</body>
</html>

      </section>
      
      <!-- Sección de Contacto -->
      <section id="#Contacto">
        <h2>Contacto</h2>
        <p>Puedes visitarnos en nuestra dirección o a través de nuestra tienda en línea.</p>
        <address>
          <p><strong>Dirección:</strong> Carlos A. Carrillo, Veracruz, Colonia José López Portillo, Calle Oaxaca #22, C.P. 95340</p>
          <p><strong>Teléfono:</strong> 2882751989</p>
          <p><strong>Email:</strong> ksuarezestrada@gmail.com</p>
        </address>
      </section>
      
      <!-- Redes Sociales -->
      <section class="redes-sociales">
        <h2>Síguenos en Redes Sociales</h2>
        <a href="https://www.facebook.com/share/15tLnDMFCo/" target="_blank">
          <img src="imagenes/Logotipos/Facebook.png" width="8%" height="50" alt="Facebook">
        </a>
        <a href="https://www.instagram.com/kse_invitaciones?igsh=MWMzMjV5cm9vM2huMQ==" target="_blank">
          <img src="imagenes/Logotipos/Instagram.png" width="50" height="50" alt="Instagram">
        </a>
      </section>
      
      <!-- Video de Presentación -->
      <section>
        <h2>Video de Presentación</h2>
        <object data="Video/Video 1.mp4" width="500" height="400"></object>
      </section>
    </main>
    <html lang="es">

<head>
  <meta charset="UTF-8">
  <title>Perfil de Usuario</title>
  <script type="text/javascript" src="perfil.js"></script>
</head>
<body>
  <noscript>
    <p>⚠️ Por favor, habilita JavaScript para poder actualizar tu perfil.</p>
  </noscript>

  <!-- Sección de Perfil, Pedidos y Direcciones -->
  <main>
      </form>
    </section>
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Perfil de Usuario</title>
  <script type="text/javascript" src="perfil.js"></script>
</head>
<body>
  <noscript>
    <p>⚠️ Activa JavaScript para usar el sistema de perfil.</p>
  </noscript>

  <main>
    <section id="perfil">
      <h2>Crear Perfil</h2>
      <form onsubmit="return crearPerfil()">
        <label for="nombre">Nombre:</label>
        <input type="text" id="nombre" required>

        <label for="apellido">Apellido:</label>
        <input type="text" id="apellido" required>

        <label for="telefono">Teléfono:</label>
        <input type="tel" id="telefono" required>

        <label for="imagen">Imagen de Perfil:</label>
        <input type="file" id="imagen" accept="image/*">

        <label for="email">Email:</label>
        <input type="email" id="email" required>

        <label for="password">Contraseña:</label>
        <input type="password" id="password" required>

        <button type="reset">Descartar</button>
        <button type="submit">Crear Perfil</button>
      </form>
    </section>

    <section id="vista-perfil" style="display:none;">
      <h2>Mi Perfil</h2>
      <img id="foto-perfil" src="" alt="Foto de perfil" width="120">
      <p><strong>Nombre:</strong> <span id="ver-nombre"></span></p>
      <p><strong>Email:</strong> <span id="ver-email"></span></p>
      <p><strong>Contraseña:</strong> <span id="ver-password"></span></p>
      <div class="menu">
        <button onclick="toggleMenu()">☰ Menú</button>
        <div id="menu-opciones" style="display:none;">
          <button onclick="cerrarSesion()">🔒 Cerrar Sesión</button>
        </div>
    </section>
  </main>
</body>
</html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Foto de Perfil Circular</title>
  <style>
    .perfil-circular {
      position: fixed;
      top: 10px;
      right: 10px;
    }
    .perfil-circular img {
      width: 50px;
      height: 50px;
      border-radius: 50%;
      cursor: pointer;
    }
    .menu-perfil {
      display: none;
      position: absolute;
      right: 0;
      top: 60px;
      background: white;
      border: 1px solid #ccc;
      box-shadow: 0 2px 5px rgba(0,0,0,0.2);
    }
    .menu-perfil button {
      display: block;
      width: 100%;
      border: none;
      background: none;
      padding: 10px;
      cursor: pointer;
      text-align: left;
    }
    .menu-perfil button:hover {
      background: #eee;
    }
  </style>
  <script type="text/javascript" src="perfilMini.js"></script>
</head>
<body>
  <noscript>
    <p>⚠️ Activa JavaScript para ver la foto de perfil.</p>
  </noscript>
  </div>
</body>
</html>
      <html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Productos en Espera</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            font-size: 20px;
        }
        #mensaje-espera {
            display: none;
            background-color: yellow;
            padding: 10px;
            font-weight: bold;
            border: 1px solid #ccc;
            border-radius: 5px;
            width: 200px;
            text-align: center;
        }
    </style>
</head>
<body>

    <h2>Gestión de Productos en Espera</h2>
    <button onclick="agregarProducto()">Agregar Producto en Espera</button>
    <button onclick="limpiarEspera()">Eliminar Todos</button>
    
    <div id="mensaje-espera">⚠️ Producto en espera</div>

    <script>
        document.addEventListener("DOMContentLoaded", verificarEspera);

        function agregarProducto() {
            let productosEspera = JSON.parse(localStorage.getItem("productosEspera")) || [];
            productosEspera.push("Nuevo Producto");
            localStorage.setItem("productosEspera", JSON.stringify(productosEspera));
            verificarEspera();
        }

        function limpiarEspera() {
            localStorage.removeItem("productosEspera");
            verificarEspera();
        }

        function verificarEspera() {
            let productosEspera = JSON.parse(localStorage.getItem("productosEspera")) || [];
            let mensaje = document.getElementById("mensaje-espera");

            if (productosEspera.length > 0) {
                mensaje.style.display = "block";
            } else {
                mensaje.style.display = "none";
            }
        }
    </script>

</body>
</html>

      <head>
          <meta charset="UTF-8">
          <meta name="viewport" content="width=device-width, initial-scale=1.0">
          <title>Gestión de Direcciones</title>
          <style>
              body { font-family: Arial, sans-serif; }
              .direccion { border: 1px solid #ddd; padding: 10px; margin: 5px; }
              .predeterminada { background-color: #f0f8ff; }
          </style>
      </head>
      <body>
          <h2>Gestión de Direcciones</h2>
          <input type="text" id="nuevaDireccion" placeholder="Ingresa nueva dirección">
          <button onclick="agregarDireccion()">Añadir Dirección</button>
          <div id="listaDirecciones"></div>
      
          <script>
              let direcciones = JSON.parse(localStorage.getItem("direcciones")) || [];
      
              function guardarDirecciones() {
                  localStorage.setItem("direcciones", JSON.stringify(direcciones));
                  mostrarDirecciones();
              }
      
              function agregarDireccion() {
                  let direccion = document.getElementById("nuevaDireccion").value;
                  if (direccion.trim() !== "") {
                      direcciones.push({ texto: direccion, predeterminada: direcciones.length === 0 });
                      guardarDirecciones();
                      document.getElementById("nuevaDireccion").value = "";
                  }
              }
      
              function eliminarDireccion(index) {
                  direcciones.splice(index, 1);
                  guardarDirecciones();
              }
      
              function editarDireccion(index) {
                  let nuevaDireccion = prompt("Editar dirección:", direcciones[index].texto);
                  if (nuevaDireccion !== null && nuevaDireccion.trim() !== "") {
                      direcciones[index].texto = nuevaDireccion;
                      guardarDirecciones();
                  }
              }
      
              function establecerPredeterminada(index) {
                  direcciones.forEach((dir, i) => dir.predeterminada = i === index);
                  guardarDirecciones();
              }
      
              function mostrarDirecciones() {
                  let contenedor = document.getElementById("listaDirecciones");
                  contenedor.innerHTML = "";
                  direcciones.forEach((dir, index) => {
                      let div = document.createElement("div");
                      div.className = "direccion" + (dir.predeterminada ? " predeterminada" : "");
                      div.innerHTML = `
                          ${dir.texto} 
                          <button onclick="editarDireccion(${index})">✏️ Editar</button>
                          <button onclick="eliminarDireccion(${index})">🗑️ Eliminar</button>
                          ${dir.predeterminada ? "✔️ Predeterminada" : `<button onclick="establecerPredeterminada(${index})">⭐ Establecer como Predeterminada</button>`}
                      `;
                      contenedor.appendChild(div);
                  });
              }
      
              mostrarDirecciones();
          </script>
      </html>      
      <!-- Ubicación -->
      <section>
        <h2>📍 Ubicación de KSE Invitaciones</h2>
        <button onclick="window.open('https://www.google.com/maps', '_blank')">🗺 Ver en Google Maps</button>
        <h3>Vista Previa:</h3>
        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d14937.45553986286!2d-95.6594972!3d18.4307639!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x85c23a177a54b96d%3A0x86b8e77a58eb18d3!2sCalle%20Oaxaca%2022%2C%20Jos%C3%A9%20L%C3%B3pez%20Portillo%2C%20Carlos%20A.%20Carrillo%2C%20Ver.!5e0!3m2!1ses!2smx!4v1712090000000" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
      </section>
    </main>
    
    <!-- Navegación inferior -->
    <footer>
      <p>Gracias por tu preferencia, somos tu mejor opción.</p>
    </footer>
    
    <!-- Bloque de script extra encapsulado (opcional) -->
    <script>
      (function(){
        let CarritoExtra = [];
        let nTotalExtra = 0;
        function agregarAlCarritoExtra(nombre, precio) {
          CarritoExtra.push({ nombre, precio });
          nTotalExtra += precio;
          console.log("Carrito Extra:", CarritoExtra, "Total:", nTotalExtra);
        }
        // Exponer funciones para pruebas si se requieren
        window.agregarAlCarritoExtra = agregarAlCarritoExtra;
      })();
    </script>
  </body>
</html>
