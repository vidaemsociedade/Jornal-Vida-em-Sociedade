<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jornal Vida em Sociedade</title>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Source+Sans+Pro:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Source Sans Pro', sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #fff;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        /* Header */
        .header {
            border-bottom: 3px solid #000;
            padding: 20px 0;
            margin-bottom: 30px;
        }

        .header-top {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 10px;
            font-size: 14px;
            color: #666;
        }

        .date {
            font-weight: 300;
        }

        .edition {
            font-weight: 600;
        }

        .newspaper-title {
            text-align: center;
            font-family: 'Playfair Display', serif;
            font-size: 3.5rem;
            font-weight: 700;
            color: #000;
            letter-spacing: 2px;
            margin: 10px 0;
        }

        .subtitle {
            text-align: center;
            font-style: italic;
            color: #666;
            font-size: 16px;
            margin-bottom: 20px;
        }

        /* Navigation */
        .nav {
            background-color: #000;
            padding: 10px 0;
            margin-bottom: 30px;
        }

        .nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            gap: 30px;
        }

        .nav a {
            color: #fff;
            text-decoration: none;
            font-weight: 600;
            text-transform: uppercase;
            font-size: 14px;
            padding: 5px 10px;
            transition: background-color 0.3s;
        }

        .nav a:hover {
            background-color: #333;
        }

        /* Main Content */
        .main-content {
            display: grid;
            grid-template-columns: 2fr 1fr 1fr;
            gap: 30px;
            margin-bottom: 40px;
        }

        /* Headlines */
        .headline {
            border-bottom: 2px solid #000;
            padding-bottom: 20px;
            margin-bottom: 30px;
        }

        .headline h1 {
            font-family: 'Playfair Display', serif;
            font-size: 2.5rem;
            line-height: 1.2;
            margin-bottom: 15px;
            color: #000;
        }

        .headline .lead {
            font-size: 1.2rem;
            color: #666;
            font-weight: 300;
            line-height: 1.4;
            margin-bottom: 15px;
        }

        .headline .meta {
            font-size: 14px;
            color: #999;
        }

        /* Articles */
        .article {
            margin-bottom: 30px;
            padding-bottom: 20px;
            border-bottom: 1px solid #eee;
        }

        .article h2 {
            font-family: 'Playfair Display', serif;
            font-size: 1.5rem;
            margin-bottom: 10px;
            color: #000;
            line-height: 1.3;
        }

        .article .excerpt {
            color: #666;
            margin-bottom: 10px;
            line-height: 1.5;
        }

        .article .meta {
            font-size: 12px;
            color: #999;
            font-style: italic;
        }

        /* Sidebar Articles */
        .sidebar-article {
            margin-bottom: 25px;
            padding-bottom: 15px;
            border-bottom: 1px solid #ddd;
        }

        .sidebar-article h3 {
            font-family: 'Playfair Display', serif;
            font-size: 1.1rem;
            margin-bottom: 8px;
            color: #000;
            line-height: 1.3;
        }

        .sidebar-article .excerpt {
            font-size: 14px;
            color: #666;
            margin-bottom: 8px;
        }

        .sidebar-article .meta {
            font-size: 11px;
            color: #999;
        }

        /* Section Headers */
        .section-header {
            font-family: 'Playfair Display', serif;
            font-size: 1.3rem;
            font-weight: 700;
            color: #000;
            border-bottom: 2px solid #000;
            padding-bottom: 10px;
            margin-bottom: 20px;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        /* Footer */
        .footer {
            border-top: 2px solid #000;
            padding: 30px 0;
            margin-top: 50px;
            text-align: center;
            color: #666;
            font-size: 14px;
        }

        /* Responsive */
        @media (max-width: 768px) {
            .main-content {
                grid-template-columns: 1fr;
                gap: 20px;
            }
            
            .newspaper-title {
                font-size: 2.5rem;
            }
            
            .headline h1 {
                font-size: 2rem;
            }
            
            .nav ul {
                flex-wrap: wrap;
                gap: 15px;
            }
        }
    </style>
</head>
<body>
    <header class="header">
        <div class="container">
            <div class="header-top">
                <div class="date">Segunda-feira, 4 de Agosto de 2025</div>
                <div class="edition">Edição nº 001</div>
            </div>
            <h1 class="newspaper-title">JORNAL VIDA EM SOCIEDADE</h1>
            <p class="subtitle">Notícias que Transformam a Comunidade</p>
        </div>
    </header>

    <nav class="nav">
        <div class="container">
            <ul>
                <li><a href="#politica">Política</a></li>
                <li><a href="#economia">Economia</a></li>
                <li><a href="#sociedade">Sociedade</a></li>
                <li><a href="#cultura">Cultura</a></li>
                <li><a href="#esportes">Esportes</a></li>
                <li><a href="#internacional">Internacional</a></li>
            </ul>
        </div>
    </nav>

    <main class="container">
        <section class="main-content">
            <!-- Coluna Principal -->
            <div class="main-column">
                <article class="headline">
                    <h1>Sua Manchete Principal Aqui</h1>
                    <p class="lead">Este é o lead da sua notícia principal. Aqui você deve resumir os pontos mais importantes da matéria em algumas linhas para despertar o interesse do leitor.</p>
                    <div class="meta">Por: Seu Nome | 4 de agosto de 2025</div>
                </article>

                <article class="article">
                    <h2>Segunda Notícia Importante</h2>
                    <p class="excerpt">Aqui você pode colocar um resumo da segunda notícia mais importante do dia. Mantenha sempre um texto claro e objetivo.</p>
                    <div class="meta">Por: Editor | Hoje às 14:30</div>
                </article>

                <article class="article">
                    <h2>Terceira Notícia em Destaque</h2>
                    <p class="excerpt">Continue adicionando suas notícias seguindo este formato. Você pode copiar e colar este bloco quantas vezes precisar.</p>
                    <div class="meta">Por: Redação | Hoje às 12:15</div>
                </article>
            </div>

            <!-- Segunda Coluna -->
            <div class="second-column">
                <h2 class="section-header">Política</h2>
                
                <article class="sidebar-article">
                    <h3>Notícia Política 1</h3>
                    <p class="excerpt">Resumo da notícia política em algumas linhas...</p>
                    <div class="meta">Há 2 horas</div>
                </article>

                <article class="sidebar-article">
                    <h3>Notícia Política 2</h3>
                    <p class="excerpt">Resumo da segunda notícia política...</p>
                    <div class="meta">Há 4 horas</div>
                </article>

                <h2 class="section-header">Economia</h2>
                
                <article class="sidebar-article">
                    <h3>Notícia Econômica</h3>
                    <p class="excerpt">Resumo da notícia econômica...</p>
                    <div class="meta">Ontem</div>
                </article>
            </div>

            <!-- Terceira Coluna -->
            <div class="third-column">
                <h2 class="section-header">Sociedade</h2>
                
                <article class="sidebar-article">
                    <h3>Notícia Social 1</h3>
                    <p class="excerpt">Resumo da notícia social...</p>
                    <div class="meta">Há 1 hora</div>
                </article>

                <article class="sidebar-article">
                    <h3>Notícia Social 2</h3>
                    <p class="excerpt">Resumo da segunda notícia social...</p>
                    <div class="meta">Há 3 horas</div>
                </article>

                <h2 class="section-header">Cultura</h2>
                
                <article class="sidebar-article">
                    <h3>Evento Cultural</h3>
                    <p class="excerpt">Resumo do evento cultural...</p>
                    <div class="meta">Hoje</div>
                </article>

                <article class="sidebar-article">
                    <h3>Arte Local</h3>
                    <p class="excerpt">Notícia sobre arte local...</p>
                    <div class="meta">Ontem</div>
                </article>
            </div>
        </section>
    </main>

    <footer class="footer">
        <div class="container">
            <p>&copy; 2025 Jornal Vida em Sociedade. Todos os direitos reservados.</p>
            <p>Contato: contato@vidaemsociedade.com.br</p>
        </div>
    </footer>
</body>
</html>
