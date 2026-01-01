<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Minha Empresa - Site Simples</title>
    <style>
        /* Reset básico */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* Corpo da página */
        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #f4f4f4;
            display: flex;
            flex-direction: column;
            min-height: 100vh;
        }

        /* Cabeçalho */
        header {
            background-color: #007bff;
            color: white;
            padding: 20px;
            text-align: center;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }

        header h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
        }

        header p {
            font-size: 1.2em;
        }

        /* Seção de apresentação */
        .apresentacao {
            flex: 1;
            padding: 40px 20px;
            text-align: center;
            background-color: white;
            margin: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }

        .apresentacao h2 {
            font-size: 2em;
            margin-bottom: 20px;
            color: #007bff;
        }

        .apresentacao p {
            font-size: 1.1em;
            max-width: 600px;
            margin: 0 auto;
        }

        /* Botão de contato WhatsApp */
        .whatsapp-btn {
            display: inline-block;
            background-color: #25d366;
            color: white;
            padding: 15px 30px;
            text-decoration: none;
            font-size: 1.2em;
            border-radius: 5px;
            margin: 20px;
            transition: background-color 0.3s;
            box-shadow: 0 2px 5px rgba(0,0,0,0.2);
        }

        .whatsapp-btn:hover {
            background-color: #128c7e;
        }

        /* Responsividade */
        @media (max-width: 768px) {
            header h1 {
                font-size: 2em;
            }

            .apresentacao {
                margin: 10px;
                padding: 20px;
            }

            .apresentacao h2 {
                font-size: 1.5em;
            }

            .whatsapp-btn {
                padding: 12px 25px;
                font-size: 1em;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Minha Empresa</h1>
        <p>Soluções inovadoras para o seu negócio</p>
    </header>

    <section class="apresentacao">
        <h2>Bem-vindo à Minha Empresa</h2>
        <p>Somos uma empresa dedicada a oferecer serviços de alta qualidade para atender às suas necessidades. Com anos de experiência no mercado, focamos em inovação, eficiência e satisfação do cliente. Explore nossas soluções e entre em contato para saber mais sobre como podemos ajudar o seu negócio a crescer.</p>
    </section>

    <a href="https://wa.me/5511999999999?text=Olá,%20gostaria%20de%20saber%20mais%20sobre%20seus%20serviços!" class="whatsapp-btn" target="_blank">
        Contato via WhatsApp
    </a>
</body>
</html># meusite
