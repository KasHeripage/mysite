<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Moda Street e Clássica</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f7f7f7;
            color: #333;
        }
        header {
            background-color: #f4a8a3;
            color: #fff;
            padding: 20px;
            text-align: center;
            font-size: 2em;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        nav {
            margin: 20px;
            text-align: center;
        }
        nav a {
            color: #f4a8a3;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            width: 80%;
            margin: 0 auto;
            padding: 20px;
        }
        section {
            margin-bottom: 40px;
        }
        .section-title {
            font-size: 1.5em;
            color: #f4a8a3;
            border-bottom: 2px solid #f4a8a3;
            padding-bottom: 10px;
            margin-bottom: 20px;
        }
        .tips, .about, .contact {
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            padding: 20px;
        }
        .tips img, .about img {
            max-width: 100%;
            border-radius: 8px;
        }
        .contact form {
            display: flex;
            flex-direction: column;
        }
        .contact input, .contact textarea {
            margin-bottom: 10px;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 4px;
        }
        .contact button {
            background-color: #f4a8a3;
            border: none;
            color: #fff;
            padding: 10px;
            border-radius: 4px;
            cursor: pointer;
            font-size: 1em;
        }
        .contact button:hover {
            background-color: #e47f77;
        }
        footer {
            background-color: #f4a8a3;
            color: #fff;
            text-align: center;
            padding: 10px;
            font-size: 0.9em;
        }
    </style>
</head>
<body>
    <header>
        Moda Street e Clássica
    </header>
    <nav>
        <a href="#tips">Dicas</a>
        <a href="#about">Sobre</a>
        <a href="#contact">Contato</a>
    </nav>
    <div class="container">
        <section id="tips" class="tips">
            <div class="section-title">Dicas de Moda</div>
            <p>Descubra como misturar o estilo street com o clássico/vintage para criar looks únicos e modernos. Aqui estão algumas dicas para você se inspirar:</p>
            <ul>
                <li><strong>Combine peças clássicas com acessórios modernos:</strong> Um blazer vintage pode ganhar um toque moderno com um boné street style.</li>
                <li><strong>Experimente camadas:</strong> Misture camisas clássicas com jaquetas oversized para um look contemporâneo.</li>
                <li><strong>Brinque com texturas e estampas:</strong> A combinação de padrões e tecidos pode criar um visual sofisticado e atual.</li>
            </ul>
            <img src="https://via.placeholder.com/800x400" alt="Dicas de Moda">
        </section>
        <section id="about" class="about">
            <div class="section-title">Sobre</div>
            <p>Bem-vindo ao nosso site de moda! Aqui, exploramos a interseção entre o estilo street e o clássico/vintage, trazendo para você as melhores dicas e tendências. Nosso objetivo é ajudar você a criar um estilo pessoal que combine o melhor dos dois mundos.</p>
            <img src="https://via.placeholder.com/800x400" alt="Sobre">
        </section>
        <section id="contact" class="contact">
            <div class="section-title">Contato</div>
            <form action="mailto:seuemail@example.com" method="post" enctype="text/plain">
                <input type="text" name="name" placeholder="Seu Nome" required>
                <input type="email" name="email" placeholder="Seu Email" required>
                <textarea name="message" rows="5" placeholder="Sua Mensagem" required></textarea>
                <button type="submit">Enviar Mensagem</button>
            </form>
        </section>
    </div>
    <footer>
        &copy; 2024 Moda Street e Clássica. Todos os direitos reservados.
    </footer>
</body>
</html>
