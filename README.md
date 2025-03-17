<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Modasbayola - Contacto</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap');
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
        }
        
        body {
            background-color: #0a1930;
            color: white;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
        }
        
        .container {
            width: 90%;
            max-width: 500px;
            margin: 20px auto;
            border-radius: 24px;
            overflow: hidden;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.4);
            animation: fadeIn 1s ease;
        }
        
        .header {
            background: linear-gradient(135deg, #ff6b9c 0%, #7366ff 100%);
            padding: 30px 20px;
            text-align: center;
            position: relative;
        }
        
        .logo-container {
            margin-bottom: 20px;
        }
        
        .logo {
            font-size: 42px;
            font-weight: 700;
            letter-spacing: 1px;
            text-transform: lowercase;
            background: linear-gradient(to right, #fff, #e2e2e2);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            text-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
        }
        
        .tagline {
            font-size: 14px;
            opacity: 0.9;
            margin-top: 5px;
            font-weight: 300;
        }
        
        .content {
            background: linear-gradient(145deg, #e94ba1 0%, #8a2be2 100%);
            padding: 30px 20px;
            display: flex;
            flex-direction: column;
            gap: 20px;
        }
        
        .contact-btn {
            display: flex;
            align-items: center;
            padding: 16px 24px;
            border-radius: 12px;
            text-decoration: none;
            color: white;
            font-weight: 600;
            transition: all 0.3s ease;
            position: relative;
            overflow: hidden;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
        }
        
        .contact-btn i {
            font-size: 24px;
            margin-right: 15px;
            position: relative;
            z-index: 2;
        }
        
        .contact-btn span {
            position: relative;
            z-index: 2;
            font-size: 18px;
        }
        
        .contact-btn:before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(255, 255, 255, 0.1);
            transform: translateX(-100%);
            transition: transform 0.4s ease;
        }
        
        .contact-btn:hover:before {
            transform: translateX(0);
        }
        
        .contact-btn:active {
            transform: scale(0.98);
        }
        
        .email-btn {
            background: linear-gradient(to right, #2196F3, #0d47a1);
        }
        
        .phone-btn {
            background: linear-gradient(to right, #4CAF50, #2E7D32);
        }
        
        .instagram-btn {
            background: linear-gradient(45deg, #f09433 0%, #e6683c 25%, #dc2743 50%, #cc2366 75%, #bc1888 100%);
        }
        
        .whatsapp-btn {
            background: linear-gradient(to right, #25D366, #128C7E);
        }
        
        .footer {
            background-color: rgba(0, 0, 0, 0.7);
            padding: 15px;
            text-align: center;
            font-size: 12px;
            color: #aaa;
        }
        
        .trust-badges {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 15px;
        }
        
        .trust-badge {
            background-color: rgba(255, 255, 255, 0.1);
            border-radius: 8px;
            padding: 8px 15px;
            font-size: 12px;
            display: flex;
            align-items: center;
            gap: 5px;
        }
        
        .trust-badge i {
            font-size: 14px;
        }
        
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        
        @media (max-width: 400px) {
            .container {
                width: 95%;
            }
            
            .contact-btn {
                padding: 14px 18px;
            }
            
            .contact-btn i {
                font-size: 20px;
                margin-right: 10px;
            }
            
            .contact-btn span {
                font-size: 16px;
            }
            
            .trust-badges {
                flex-wrap: wrap;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <div class="logo-container">
                <h1 class="logo">modasbayola</h1>
                <p class="tagline">Estilo • Elegancia • Distinción</p>
            </div>
        </div>
        
        <div class="content">
            <a href="mailto:modasbayola@gmail.com" class="contact-btn email-btn">
                <i class="fas fa-envelope"></i>
                <span>Correo Electrónico</span>
            </a>
            
            <a href="tel:++5403564383297" class="contact-btn phone-btn">
                <i class="fas fa-phone-alt"></i>
                <span>Teléfono</span>
            </a>
            
            <a href="https://www.instagram.com/modasbayola?igsh=MWpxa3MzN2FqNHZzZA==" class="contact-btn instagram-btn">
                <i class="fab fa-instagram"></i>
                <span>Instagram</span>
            </a>
            
            <a href="https://wa.me/+5403564383297" class="contact-btn whatsapp-btn">
                <i class="fab fa-whatsapp"></i>
                <span>WhatsApp</span>
            </a>
            
            <div class="trust-badges">
                <div class="trust-badge">
                    <i class="fas fa-lock"></i> Sitio Seguro
                </div>
                <div class="trust-badge">
                    <i class="fas fa-star"></i> Calidad Garantizada
                </div>
            </div>
        </div>
        
        <div class="footer">
            © 2025 Modasbayola - Todos los derechos reservados
        </div>
    </div>
</body>
</html>
