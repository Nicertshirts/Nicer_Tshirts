# Nicer_Tshirts
Shop
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>NICER TSHIRTS</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f8f8f8;
      margin: 0;
      padding: 0;
      text-align: center;
      color: #333;
    }

    header {
      background: #fff;
      padding: 20px;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    }

    header img {
      height: 80px;
    }

    h1 {
      margin: 10px 0 0;
      font-size: 28px;
      color: #d60000;
    }

    /* Estilo para el enlace */
    .header-link {
      display: inline-block;
      margin-top: 8px;
      font-size: 16px;
      color: #d60000;
      text-decoration: none;
      font-weight: bold;
    }

    .header-link:hover {
      text-decoration: underline;
    }

    .producto {
      margin: 30px auto;
      max-width: 600px;
      background: #fff;
      padding: 20px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      border-radius: 8px;
    }

    .producto img {
      max-width: 100%;
      border-radius: 6px;
    }

    .producto-detalles {
      margin-top: 20px;
      text-align: left;
    }

    .producto-detalles h2 {
      font-size: 24px;
      color: #c20000;
    }

    .precios {
      list-style: none;
      padding: 0;
    }

    .precios li {
      margin: 8px 0;
    }

    form {
      margin-top: 20px;
    }
  </style>
</head>
<body>

  <header>
    <img src="F0A82D3B-3009-4954-8B06-126714935C3E.jpeg" alt="Logo NICER" />
    <h1>NICER TSHIRTS</h1>
    <a class="header-link" href="https://www.nicer_tshirts.com" target="_blank" rel="noopener noreferrer">
      Visita www.nicer_tshirts.com
    </a>
  </header>

  <div class="producto">
    <img src="ACBECFC2-03BF-4849-B1E5-1A442CB8D6F7.jpeg" alt="Camiseta Manchester United 2008 CR7" />
    
    <div class="producto-detalles">
      <h2>CAMISETA MÁNCHESTER UNITED 2008 CR7</h2>
      <p>Revive la final de Moscú con esta réplica de la camiseta del Mánchester United 2008 usada por Cristiano Ronaldo. Calidad premium. Manga larga. Ideal para coleccionistas y fans.</p>
      <ul class="precios">
        <li><strong>Precio:</strong> 25€</li>
        <li><strong>Envío incluido:</strong> 5€</li>
        <li><strong>Total:</strong> 30€</li>
        <li><strong>Tiempo estimado de envío:</strong> 15 días</li>
      </ul>

      <!-- Botón PayPal -->
      <form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_blank">
        <input type="hidden" name="cmd" value="_xclick" />
        <input type="hidden" name="business" value="alexvicenhernan@gmail.com" />
        <input type="hidden" name="item_name" value="Camiseta Manchester United 2008 CR7" />
        <input type="hidden" name="amount" value="30.00" />
        <input type="hidden" name="currency_code" value="EUR" />
        <input
          type="image"
          src="https://www.paypalobjects.com/es_XC/i/btn/btn_buynow_LG.gif"
          border="0"
          name="submit"
          alt="Pagar con PayPal"
        />
        <img alt="" border="0" src="https://www.paypal.com/es_XC/i/scr/pixel.gif" width="1" height="1" />
      </form>
    </div>
  </div>

</body>
</html>
