<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>SSP StructoRevive</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(to right, #004466, #0088aa);
      color: #fff;
      display: flex;
      align-items: center;
      justify-content: center;
      height: 100vh;
      animation: fadeIn 2s ease-in;
    }

    .container {
      text-align: center;
      animation: slideUp 1s ease-out;
    }

    h1 {
      font-size: 2.8rem;
      margin-bottom: 10px;
      animation: fadeInUp 1.2s ease-out;
    }

    h2 {
      font-size: 1.5rem;
      margin-bottom: 25px;
      font-weight: normal;
      animation: fadeInUp 1.5s ease-out;
    }

    .services {
      font-size: 1.1rem;
      margin-bottom: 30px;
      letter-spacing: 2px;
      animation: fadeInUp 1.8s ease-out;
    }

    .contact {
      font-size: 1rem;
      animation: fadeInUp 2s ease-out;
    }

    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }

    @keyframes slideUp {
      from { transform: translateY(30px); opacity: 0; }
      to { transform: translateY(0); opacity: 1; }
    }

    @keyframes fadeInUp {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>SSP STRUCTOREVIVE</h1>
    <h2>Garia, Kolkata – 700154</h2>
    <div class="services">WATERPROOFING | REPAIRS | PAINTING</div>
    <div class="contact">
      Email: sspstructorevive@gmail.com<br>
      Phone: 7407607375
    </div>
  </div>
</body>
</html>
