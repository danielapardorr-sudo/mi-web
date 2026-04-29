<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Fan Page Oficial</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: linear-gradient(135deg, #ff9a9e, #fad0c4);
      text-align: center;
      color: #333;
      padding: 40px;
    }
    .card {
      background: white;
      border-radius: 20px;
      padding: 30px;
      max-width: 500px;
      margin: auto;
      box-shadow: 0 10px 25px rgba(0,0,0,0.2);
    }
    h1 {
      color: #ff4b5c;
    }
    button {
      background: #ff4b5c;
      color: white;
      border: none;
      padding: 15px 25px;
      border-radius: 10px;
      cursor: pointer;
      font-size: 16px;
      margin-top: 20px;
    }
    button:hover {
      background: #ff1e3c;
    }
    #mensaje {
      margin-top: 20px;
      font-weight: bold;
    }
  </style>
</head>
<body>

  <div class="card">
    <h1>💖 ESTUPIDO 💖</h1>
    <p>Bienvenida a la página oficial donde recordamos lo increíble que eres 😎</p>

    <button onclick="mostrarMensaje()">Pulsa aquí</button>

    <p id="mensaje"></p>
  </div>

  <script>
    function mostrarMensaje() {
      const mensajes = [
        "Eres la amiga mas subnormal del mundo 🌍",
        "Nunca olvides lo puta que eres ✨",
        "Gilipollas 😎",
        "Lameescrotos 😂",
        "Guarra 💖",
        "Si fueras una gamba, yo sería alergica al marisco",
        "Si vas a facer cositas delante de un bmw, que no sea el de los padres de tu amiga",
        "Eres como un WiFi público: lento, inseguro y nadie confía en ti.",
        "Tienes menos luces que un apagón en el Polo Norte.",
        "Si la inteligencia fuera dinero, estarías en bancarrota.",
        "Eres tan útil como un paraguas en un submarino.",
        "Tu lógica es como un GPS roto: siempre te lleva al sitio equivocado.",
        "Eres la prueba de que el modo “automático” también falla.",
        "Tienes más excusas que soluciones.",
        "Eres como un spoiler mal contado: molesto y sin gracia.",
        "Eres tan irrelevante que ni el eco te responde.",
        "Tienes el talento oculto… tan oculto que nadie lo ha encontrado.",
        "Eres el borrador de una mala idea.",
        "Si fueras silencio, al menos aportarías algo.",
        "Tu presencia es como un error 404: nadie pidió que aparecieras.",
        "Eres el ‘etcétera’ de una conversación aburrida.",
        "Si fueras profundidad, serías un charco en verano.",
        "Tu argumento tiene menos peso que una pluma en el vacío.",
        "Eres la versión beta… y nunca saliste de pruebas.",
        "Si te explicas más, te entiendes menos."
      ];

      const random = Math.floor(Math.random() * mensajes.length);
      document.getElementById("mensaje").innerText = mensajes[random];
    }
  </script>

</body>
</html>
