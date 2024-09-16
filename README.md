
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Poupinha do Piseiro - Juazeiro do Norte</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: #ffffff;
            background-color: #000000;
        }
        header {
            background-color: #ffcc00;
            color: #000000;
            padding: 20px;
            text-align: center;
        }
        nav {
            margin: 0;
            padding: 0;
            background-color: #333333;
            color: #ffffff;
            text-align: center;
        }
        nav a {
            color: #ffffff;
            padding: 14px 20px;
            display: inline-block;
            text-decoration: none;
        }
        .container {
            padding: 20px;
        }
        .section {
            margin-bottom: 20px;
        }
        footer {
            background-color: #ffcc00;
            color: #000000;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        .google-map {
            width: 100%;
            height: 400px;
            border: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Poupinha do Piseiro</h1>
        <p>Juazeiro do Norte, Ceará - BR</p>
    </header>

    <nav>
        <a href="#sobre">Sobre</a>
        <a href="#contato">Contato</a>
        <a href="#localizacao">Localização</a>
    </nav>

    <div class="container">
        <section id="sobre" class="section">
            <h2>Sobre</h2>
            <p>Bem-vindo ao site de Poupinha do Piseiro! Aqui você encontrará todas as informações sobre nossas apresentações, novidades e muito mais. Fique ligado!</p>
        </section>

        <section id="contato" class="section">
            <h2>Contato</h2>
            <p>Você pode entrar em contato conosco pelo e-mail: <a href="mailto:contato@poupinhadopiseiro.com">contato@poupinhadopiseiro.com</a></p>
        </section>

        <section id="localizacao" class="section">
            <h2>Localização</h2>
            <p>Veja nossa localização no mapa abaixo:</p>
            <!-- Google Maps Embed -->
            <iframe class="google-map" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3946.5071265854086!2d-39.3248666!3d-7.2207788!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x7b83b3b8f76f1eb%3A0x68f7e1cf77deed7f!2sJuazeiro%20do%20Norte%2C%20CE%2C%20Brasil!5e0!3m2!1spt-BR!2sus!4v1687248624375!5m2!1spt-BR!2sus" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 Poupinha do Piseiro. Todos os direitos reservados.</p>
    </footer>

    <!-- Google Translate Script -->
    <div id="google_translate_element"></div>
    <script type="text/javascript">
        function googleTranslateElementInit() {
            new google.translate.TranslateElement({pageLanguage: 'pt'}, 'google_translate_element');
        }
    </script>
    <script type="text/javascript" src="https://translate.google.com/translate_a/element.js?cb=googleTranslateElementInit"></script>
</body>
</html>
