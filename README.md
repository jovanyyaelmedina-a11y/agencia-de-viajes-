# agencia-de-viajes-
seguro y rápido

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Agencia de Viajes - Horizontes</title>
    <style>
        :root {
            --primary: #0284c7;
            --primary-dark: #0369a1;
            --secondary: #0ea5e9;
            --text-main: #1e293b;
            --text-light: #64748b;
            --bg-light: #f8fafc;
            --white: #ffffff;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: var(--bg-light);
            color: var(--text-main);
            line-height: 1.6;
        }

        header {
            background: linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.6)), url('https://images.unsplash.com/photo-1469854523086-cc02fe5d8800?auto=format&fit=crop&w=1200&q=80') no-repeat center center/cover;
            color: var(--white);
            text-align: center;
            padding: 100px 20px;
        }

        header h1 {
            font-size: 3rem;
            margin-bottom: 10px;
        }

        header p {
            font-size: 1.2rem;
            font-weight: 300;
        }

        .container {
            max-width: 1200px;
            margin: 40px auto;
            padding: 0 20px;
        }

        .destinos-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            margin-top: 30px;
        }

        .card {
            background-color: var(--white);
            border-radius: 12px;
            overflow: hidden;
            box-shadow: 0 4px 15px rgba(0,0,0,0.05);
            transition: transform 0.3s ease;
        }

        .card:hover {
            transform: translateY(-5px);
        }

        .card-img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }

        .card-content {
            padding: 25px;
        }

        .card-title {
            font-size: 1.5rem;
            color: var(--text-main);
            margin-bottom: 15px;
            border-bottom: 2px solid var(--bg-light);
            padding-bottom: 10px;
        }

        .info-row {
            display: flex;
            justify-content: space-between;
            margin-bottom: 12px;
            font-size: 0.95rem;
        }

        .info-label {
            color: var(--text-light);
            font-weight: 500;
        }

        .info-value {
            font-weight: 600;
            color: var(--text-main);
        }

        .info-value.total {
            color: var(--primary-dark);
            font-size: 1.2rem;
        }

        .btn-reserva {
            display: block;
            width: 100%;
            padding: 12px;
            background-color: var(--primary);
            color: var(--white);
            text-align: center;
            text-decoration: none;
            border-radius: 6px;
            font-weight: bold;
            margin-top: 20px;
            transition: background-color 0.2s ease;
        }

        .btn-reserva:hover {
            background-color: var(--primary-dark);
        }

        footer {
            background-color: var(--text-main);
            color: var(--white);
            text-align: center;
            padding: 20px;
            margin-top: 60px;
            font-size: 0.9rem;
        }
    </style>
</head>
<body>

    <header>
        <h1>Agencia de Viajes Horizontes</h1>
        <p>Descubre tu próximo destino al mejor precio garantizado</p>
    </header>

    <div class="container">
        <h2 style="text-align: center; color: var(--text-main);">Nuestros Destinos Destacados</h2>
        
        <div class="destinos-grid">

            <div class="card">
                <img src="https://images.unsplash.com/photo-1502602898657-3e91760cbb34?auto=format&fit=crop&w=400&q=80" alt="París" class="card-img">
                <div class="card-content">
                    <h3 class="card-title">París, Francia</h3>
                    <div class="info-row">
                        <span class="info-label">Vuelo (Ida y vuelta):</span>
                        <span class="info-value">$650 USD</span>
                    </div>
                    <div class="info-row">
                        <span class="info-label">Hospedaje (5 noches):</span>
                        <span class="info-value">$450 USD</span>
                    </div>
                    <div class="info-row" style="margin-top: 15px; padding-top: 15px; border-top: 1px dashed #e2e8f0;">
                        <span class="info-label" style="font-weight: bold;">Precio Total estimado:</span>
                        <span class="info-value total">$1,100 USD</span>
                    </div>
                    <a href="#" class="btn-reserva">Reservar Ahora</a>
                </div>
            </div>

            <div class="card">
                <img src="https://images.unsplash.com/photo-1493976040374-85c8e12f0c0e?auto=format&fit=crop&w=400&q=80" alt="Tokio" class="card-img">
                <div class="card-content">
                    <h3 class="card-title">Tokio, Japón</h3>
                    <div class="info-row">
                        <span class="info-label">Vuelo (Ida y vuelta):</span>
                        <span class="info-value">$950 USD</span>
                    </div>
                    <div class="info-row">
                        <span class="info-label">Hospedaje (5 noches):</span>
                        <span class="info-value">$500 USD</span>
                    </div>
                    <div class="info-row" style="margin-top: 15px; padding-top: 15px; border-top: 1px dashed #e2e8f0;">
                        <span class="info-label" style="font-weight: bold;">Precio Total estimado:</span>
                        <span class="info-value total">$1,450 USD</span>
                    </div>
                    <a href="#" class="btn-reserva">Reservar Ahora</a>
                </div>
            </div>

            <div class="card">
                <img src="https://images.unsplash.com/photo-1510414842594-a61c69b5ae57?auto=format&fit=crop&w=400&q=80" alt="Cancún" class="card-img">
                <div class="card-content">
                    <h3 class="card-title">Cancún, México</h3>
                    <div class="info-row">
                        <span class="info-label">Vuelo (Ida y vuelta):</span>
                        <span class="info-value">$300 USD</span>
                    </div>
                    <div class="info-row">
                        <span class="info-label">Hospedaje Todo Incluido (5 n):</span>
                        <span class="info-value">$600 USD</span>
                    </div>
                    <div class="info-row" style="margin-top: 15px; padding-top: 15px; border-top: 1px dashed #e2e8f0;">
                        <span class="info-label" style="font-weight: bold;">Precio Total estimado:</span>
                        <span class="info-value total">$900 USD</span>
                    </div>
                    <a href="#" class="btn-reserva">Reservar Ahora</a>
                </div>
            </div>

            <div class="card">
                <img src="https://images.unsplash.com/photo-1552832230-c0197dd311b5?auto=format&fit=crop&w=400&q=80" alt="Roma" class="card-img">
                <div class="card-content">
                    <h3 class="card-title">Roma, Italia</h3>
                    <div class="info-row">
                        <span class="info-label">Vuelo (Ida y vuelta):</span>
                        <span class="info-value">$700 USD</span>
                    </div>
                    <div class="info-row">
                        <span class="info-label">Hospedaje (5 noches):</span>
                        <span class="info-value">$380 USD</span>
                    </div>
                    <div class="info-row" style="margin-top: 15px; padding-top: 15px; border-top: 1px dashed #e2e8f0;">
                        <span class="info-label" style="font-weight: bold;">Precio Total estimado:</span>
                        <span class="info-value total">$1,080 USD</span>
                    </div>
                    <a href="#" class="btn-reserva">Reservar Ahora</a>
                </div>
            </div>

            <div class="card">
                <img src="https://images.unsplash.com/photo-1496442226666-8d4d0e62e6e9?auto=format&fit=crop&w=400&q=80" alt="Nueva York" class="card-img">
                <div class="card-content">
                    <h3 class="card-title">Nueva York, EE. UU.</h3>
                    <div class="info-row">
                        <span class="info-label">Vuelo (Ida y vuelta):</span>
                        <span class="info-value">$450 USD</span>
                    </div>
                    <div class="info-row">
                        <span class="info-label">Hospedaje (5 noches):</span>
                        <span class="info-value">$700 USD</span>
                    </div>
                    <div class="info-row" style="margin-top: 15px; padding-top: 15px; border-top: 1px dashed #e2e8f0;">
                        <span class="info-label" style="font-weight: bold;">Precio Total estimado:</span>
                        <span class="info-value total">$1,150 USD</span>
                    </div>
                    <a href="#" class="btn-reserva">Reservar Ahora</a>
                </div>
            </div>

        </div>
    </div>

    <footer>
        <p>&copy; 2026 Agencia de Viajes Horizontes. Proyecto para fines educativos / GitHub.</p>
    </footer>

</body>
</html>
