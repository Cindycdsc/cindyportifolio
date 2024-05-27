<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MEU PORTIFÓLIO</title>
    <link rel="shortcut icon" type="image/x-icon" href="cindy.jpg">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap');

        body {
            font-family: 'Roboto', sans-serif;
            background-color: #1a1a1a;
            color: #fff;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #833ab4;
            background: linear-gradient(45deg, #833ab4, #a553a5, #a55f88);
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
            font-weight: 700;
        }
        nav {
            text-align: center;
            margin-top: 10px;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #fff;
            font-size: 1.2em;
            font-weight: 500;
        }
        nav a:hover {
            color: #fcb045;
        }
        section {
            padding: 20px;
        }
        .bio, .projects, .contact {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: #2a2a2a;
            border-radius: 10px;
            margin-bottom: 20px;
        }
        .projects img {
            width: 100%;
            height: auto;
            border-radius: 10px;
            transition: transform 0.3s;
        }
        .projects img:hover {
            transform: scale(1.05);
        }
        .social-links a {
            margin: 0 10px;
            color: #fff;
            font-size: 1.5em;
            text-decoration: none;
            transition: color 0.3s;
        }
        .social-links a:hover {
            color: #fcb045;
        }
        .whatsapp-link {
            display: inline-block;
            background-color: #8d25d3;
            color: #fff;
            padding: 10px 20px;
            border-radius: 25px;
            text-decoration: none;
            transition: background-color 0.3s;
        }
        .whatsapp-link:hover {
            background-color: #12338c;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #833ab4;
            background: linear-gradient(45deg, #833ab4, #a553a5, #a55f88);
            font-size: 0.9em;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>MEU PORTIFÓLIO</h1>
        <nav>
            <a href="#bio">Sobre Mim</a>
            <a href="#projects">Projetos</a>
            <a href="#contact">Contato</a>
        </nav>
    </header>
    <section id="bio" class="bio">
        <h2>Sobre Mim</h2>
        <p>Olá! Sou Cinthya, uma desenvolvedora apaixonada por tecnologia e artes e acredito fielmente que posso unir esses dois mundos!</p>
        <p>Aqui está um resumo do meu currículo:</p>
        <ul>
            <li>Atualmente estou cursando analise e desenvolvimento de sistemas, estou no primeiro periodo.</li>
            <li>ainda tenho muito a aaprender, que tal me conhecer um pouco mais? clicando em contato você consegue alguns meios para falar comigo.</li>
            <li>possuo uma aderencia muito forte em realção ao aprendizado, podendo me especializar me qualquer área em que me sou designada.</li>
        </ul>
        <p>Para mais detalhes, você pode <a href="Cinthya costa dos Santos (1).pdf" target="_blank">baixar meu currículo em PDF</a>.</p>
    </section>
    <section id="projects" class="projects">
        <h2>Meus Projetos</h2>
        <div>
            <h3>PORTIFÓLIO</h3>
            <p>este é um dos meus projetos que, como pode ver ainda está em fase de desenvlvimento e aprimoramento!</p>
            <img src="projeto1.jpg" alt="Imagem do Projeto 1">
        </div>
        <div>
            <h3>AUTOMAÇÃO</h3>
            <p>É um projeto que consiste num site de redirecionamento para atendimento ao cliente, acessando o site o úsuario tera a expeeriencia de visualizar os palnos disponiveis,formas de cadastro entre outras informações</p>
            <img src="projeto2.jpg" alt="Imagem do Projeto 2">
        </div>
        <!-- ppppppppppppppppppppppppppppppppppppppppppppppp-->
    </section>
    <section id="contact" class="contact">
        <h2>Contato</h2>
        <p>Você pode entrar em contato comigo através das minhas redes sociais ou enviar uma mensagem diretamente pelo WhatsApp.</p>
        <div class="social-links">
            <a href="https://bit.ly/3wLYfA1" target="_blank">Infojobs</a>
            <a href="https://github.com/Cindycdsc" target="_blank">GitHub</a>
            <a href="https://bit.ly/44V0sFI" target="_blank">Instagram</a>
            <!-- pppppppppppppppppppppppppppppppppppppppppppppppppppp -->
        </div>
        <a href="https://wa.me/5527997752711" target="_blank" class="whatsapp-link">Fale Comigo no WhatsApp</a>
    </section>
    <footer>
        &copy; 2024 CINDY.THE.PROGRAMER
</body>
</html>
