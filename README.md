# Tienda-online-ly-ma
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Accesorios Tech</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #f9f9f9;
      color: #333;
    }
    header {
      background: linear-gradient(90deg, #ff0000, #ffd700);
      color: white;
      padding: 2rem;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }
    .container {
      max-width: 1000px;
      margin: 2rem auto;
      padding: 0 1rem;
    }
    .hero {
      display: flex;
      flex-wrap: wrap;
      gap: 2rem;
      align-items: center;
    }
    .hero img {
      width: 100%;
      max-width: 400px;
      border-radius: 10px;
    }
    .hero-text {
      flex: 1;
    }
    .hero-text h2 {
      font-size: 2rem;
      margin-bottom: 1rem;
    }
    .hero-text p {
      font-size: 1.1rem;
      margin-bottom: 1.5rem;
    }
    .btn-comprar {
      background-color: #ff0000;
      color: white;
      padding: 0.8rem 1.5rem;
      font-size: 1.1rem;
      border: none;
      border-radius: 6px;
      cursor: pointer;
      transition: background 0.3s ease;
    }
    .btn-comprar:hover {
      background-color: #cc0000;
    }
    footer {
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
      background-color: #eee;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>

  <header>
    <h1>Accesorios Tech</h1>
    <p>Todo lo que tu celular necesita</p>
  </header>

  <div class="container">
    <div class="hero">
      <img src="https://via.placeholder.com/400x300?text=Producto+Tech" alt="Accesorios para celular" />
      <div class="hero-text">
        <h2>Potencia tu estilo con nuestros accesorios</h2>
        <p>Desde fundas resistentes hasta cargadores inteligentes y auriculares premium. Descubre lo mejor en tecnología móvil.</p>
        <button class="btn-comprar" onclick="window.location.href='https://wa.me/tu_numero_o_link_de_compra'">Comprar ahora</button>
      </div>
    </div>
  </div>

  <footer>
    &copy; 2025 Accesorios Tech. Todos los derechos reservados.
  </footer>

</body>
</html>
