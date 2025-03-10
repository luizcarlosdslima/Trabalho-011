<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Facebook</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; font-family: Arial, sans-serif; }
        body { background-color: #f0f2f5; }
        .navbar { background: #1877f2; padding: 10px; color: white; text-align: center; font-size: 24px; font-weight: bold; }
        
        .container { 
            width: 900px; 
            margin: 20px auto; 
            background: white; 
            padding: 10px; 
            border-radius: 8px; 
            box-shadow: 0 2px 4px rgba(0,0,0,0.1); 
        }

        .profile-header { text-align: center; position: relative; }
        .cover-photo { width: 100%; height: 250px; background: url('capa.jpg') no-repeat center/cover; border-radius: 8px; position: relative; }
        .profile-pic { 
            width: 120px; height: 120px; 
            border-radius: 50%; border: 4px solid white; 
            position: absolute; bottom: -60px; left: 20px; 
            background: url('perfil.jpg') no-repeat center/cover; 
        }

        .name { margin-top: 70px; font-size: 22px; font-weight: bold; text-align: left; padding-left: 20px; }
        .menu { text-align: left; padding-left: 20px; margin-top: 10px; }
        .menu a { text-decoration: none; color: #1877f2; font-size: 16px; margin: 0 10px; font-weight: bold; }

        /* Layout principal */
        .content { display: flex; gap: 20px; margin-top: 20px; }
        
        /* Coluna da apresentação */
        .left-column { 
            flex: 1; 
            background: white; 
            padding: 15px; 
            border-radius: 8px; 
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
            max-width: 280px;
        }
        .left-column img { width: 16px; height: 16px; margin-right: 5px; vertical-align: middle; }
        
        /* Coluna do feed */
        .right-column { flex: 2.5; }
        .post { 
            background: white; padding: 10px; margin-top: 20px; 
            border-radius: 8px; box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }
        .post-header { display: flex; align-items: center; font-weight: bold; }
        .post-header img { width: 40px; height: 40px; border-radius: 50%; margin-right: 10px; }
        .post-content { margin-top: 5px; }
        .post-images { display: grid; grid-template-columns: repeat(2, 1fr); gap: 5px; margin-top: 10px; }
        .post-images img { width: 100%; border-radius: 8px; }

    </style>
</head>
<body>
    <div class="navbar"> Trabalho do Facebook Marçal  </div>
    
    <div class="container">
        <div class="profile-header">
            <div class="cover-photo">
                <div class="profile-pic"></div>
            </div>
            <div class="name">IFRN - Campus Natal - Zona Norte </div>
            <div class="menu">
                <a href="#">Posts</a>
                <a href="#">Sobre</a>
                <a href="#">Menções</a>
                <a href="#">avaliações</a>
                <a href="#">Seguidores</a>
                <a href="#">Fotos</a>
                <a href="#">mais🔽</a>
            </div>
        </div>
    </div>
    
    <div class="container content">
        <div class="left-column">
            <h3>Apresentação</h3>
            <p><img src="icon-info.png" alt="Info"><strong>Página · Escola</strong> </p>
            <p><img src="icon-link.png" alt="Link"> Acesse também o nosso portal: <a href="http://bit.ly/XwqAM4">http://bit.ly/XwqAM4</a>.</p>
            <p><img src="icon-location.png" alt="Localização"> R. Brusque, 2926, Cj. Santa Catarina - Potengi, Natal, RN, Brazil</p>
            <p><img src="icon-phone.png" alt="Telefone">(84) 4006-9500</p>
            <p><img src="icon-email.png" alt="Email"> <a href="mailto:gabin.zn@ifrn.edu.br">gabin.zn@ifrn.edu.br</a></p>
            <p><img src="icon-price.png" alt="Preço"> <strong>Faixa de preço:</strong> $ </p>
            <p><img src="icon-rating.png" alt="Avaliação">Recomendado por 96% (354 avaliações)</p>
        </div>
        
        <div class="right-column">
            <div class="post">
                <div class="post-header">
                    <img src="perfil.jpg" alt="Perfil">
                    IFRN - Campus Natal - Zona Norte 
                </div>
                <div class="post-content">No alvo 🎯 
                    Ficamos felizes por poder contribuir com a realização de muitos estudantes, que é o de estudar em uma universidade. ✨
                    Mais uma vez, os nossos votos de sucesso a todos os aprovados para cursos superiores em instituições públicas de ensino pelo país por meio do Sistema de Seleção Unificada (SiSU). 🥰</div>
                <div class="post-images">
                    <img src="foto1.jpg" alt="Foto 1">
                    <img src="foto2.jpg" alt="Foto 2">
                    <img src="foto3.jpg" alt="Foto 3">
                    <img src="foto4.jpg" alt="Foto 4">
                </div>
            </div>
            <div class="post">
                <div class="post-header">
                    <img src="perfil.jpg" alt="Perfil">
                    IFRN - Campus Natal - Zona Norte 
                </div>
                <div class="post-content">No alvo 🎯 
                    Ficamos felizes por poder contribuir com a realização de muitos estudantes, que é o de estudar em uma universidade. ✨
                    Mais uma vez, os nossos votos de sucesso a todos os aprovados para cursos superiores em instituições públicas de ensino pelo país por meio do Sistema de Seleção Unificada (SiSU). 🥰</div>
                <div class="post-images">
                    <img src="foto5.jpg" alt="Foto 1">
                    <img src="foto6.jpg" alt="Foto 2">
                    <img src="foto7.jpg" alt="Foto 3">
                    <img src="foto8.jpg" alt="Foto 4">
                </div>
            </div>
        </div>
    </div>
</body>
</html>
