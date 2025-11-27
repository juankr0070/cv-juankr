<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CV-JUANKR</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            padding: 20px;
        }
        
        .container {
            background: white;
            border-radius: 15px;
            box-shadow: 0 20px 60px rgba(0, 0, 0, 0.3);
            max-width: 600px;
            width: 100%;
            padding: 60px 40px;
            text-align: center;
        }
        
        .header {
            margin-bottom: 40px;
        }
        
        .title {
            font-size: 48px;
            font-weight: 700;
            color: #667eea;
            margin-bottom: 20px;
            letter-spacing: 2px;
        }
        
        .subtitle {
            font-size: 16px;
            color: #666;
            margin-bottom: 30px;
        }
        
        .divider {
            width: 80px;
            height: 4px;
            background: linear-gradient(90deg, #667eea, #764ba2);
            margin: 0 auto 40px;
            border-radius: 2px;
        }
        
        .description {
            font-size: 15px;
            color: #555;
            line-height: 1.6;
            margin-bottom: 40px;
        }
        
        .button-container {
            margin-bottom: 30px;
        }
        
        .btn-cv {
            display: inline-block;
            padding: 16px 40px;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            text-decoration: none;
            border-radius: 50px;
            font-size: 16px;
            font-weight: 600;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            box-shadow: 0 10px 30px rgba(102, 126, 234, 0.4);
            cursor: pointer;
            border: none;
        }
        
        .btn-cv:hover {
            transform: translateY(-2px);
            box-shadow: 0 15px 40px rgba(102, 126, 234, 0.6);
        }
        
        .btn-cv:active {
            transform: translateY(0);
        }
        
        .footer {
            font-size: 12px;
            color: #999;
            margin-top: 30px;
            padding-top: 20px;
            border-top: 1px solid #eee;
        }
        
        .icon {
            font-size: 14px;
            margin-right: 8px;
        }
        
        @media print {
            body {
                background: white;
                padding: 0;
            }
            
            .container {
                box-shadow: none;
                border-radius: 0;
            }
            
            .btn-cv {
                border: 2px solid #667eea;
                color: #667eea;
                background: white;
            }
        }
        
        @media (max-width: 600px) {
            .container {
                padding: 40px 25px;
            }
            
            .title {
                font-size: 36px;
            }
            
            .btn-cv {
                padding: 14px 30px;
                font-size: 15px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <div class="title">CV-JUANKR</div>
            <div class="divider"></div>
            <div class="subtitle">Curriculum Vitae</div>
        </div>
        
        <div class="description">
            <p>Accede a mi perfil profesional completo con toda mi experiencia, competencias y proyectos.</p>
        </div>
        
        <div class="button-container">
            <a href="mi-cvPC.html" class="btn-cv" target="_blank" rel="noopener noreferrer">
                <span class="icon">📄</span>Ver CV Completo
            </a>
        </div>
        
        <div class="footer">
            <p>✅ Tu CV - Abre directamente</p>
        </div>
    </div>
</body>
</html>
