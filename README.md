<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Grupo Alencar Veloso</title>
    <style>
        /* Estilos CSS básicos para dar uma aparência */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }

        header {
            background-color: #004d99; /* Um azul escuro para o cabeçalho */
            color: white;
            padding: 20px 0;
            text-align: center;
        }

        h1 {
            margin: 0;
        }

        main {
            padding: 20px;
            max-width: 900px;
            margin: auto;
        }

        section {
            background-color: white;
            padding: 20px;
            margin-bottom: 30px;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        h2 {
            color: #004d99;
            border-bottom: 2px solid #ccc;
            padding-bottom: 10px;
            margin-top: 0;
        }

        .colaboradores-lista {
            list-style: none;
            padding: 0;
        }

        .colaboradores-lista li {
            background-color: #e6f0ff; /* Fundo mais claro para os itens */
            margin-bottom: 10px;
            padding: 10px;
            border-left: 5px solid #004d99;
            border-radius: 4px;
        }

        .contato form {
            display: grid;
            grid-template-columns: 1fr;
            gap: 15px;
        }

        .contato label {
            font-weight: bold;
            display: block;
            margin-bottom: 5px;
        }

        .contato input[type="text"],
        .contato input[type="email"],
        .contato textarea {
            width: 100%;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
            box-sizing: border-box; /* Garante que o padding não aumente a largura total */
        }

        .contato button {
            background-color: #008cba; /* Azul ciano para o botão */
            color: white;
            padding: 10px 15px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            font-size: 16px;
            transition: background-color 0.3s;
        }

        .contato button:hover {
            background-color: #005f7d;
        }
    </style>
</head>
<body>

    <header>
        <h1>GRUPO ALENCAR VELOSO</h1>
        <p>Soluções e Parcerias Estratégicas</p>
    </header>

    <main>
        
        <section class="colaboradores">
            <h2>Nossos Colaboradores</h2>
            <p>Conheça os membros essenciais que fazem o Grupo Alencar Veloso crescer.</p>
            
            <ul class="colaboradores-lista">
                <li>**João da Silva:** Gerente de Projetos - Responsável pela coordenação de novas iniciativas.</li>
                <li>**Maria Souza:** Analista Financeira Sênior - Especialista em planejamento e controle orçamentário.</li>
                <li>**Pedro Oliveira:** Desenvolvedor Web Full Stack - Cuida da infraestrutura e desenvolvimento digital.</li>
                </ul>
            
            <p>Para informações sobre vagas, entre em contato pela área abaixo.</p>
        </section>

        <section class="contato">
            <h2>Fale Conosco</h2>
            <p>Entre em contato para dúvidas, propostas de parceria ou informações sobre nossos serviços.</p>

            <form action="#" method="POST">
                
                <div>
                    <label for="nome">Nome:</label>
                    <input type="text" id="nome" name="nome" required>
                </div>
                
                <div>
                    <label for="email">E-mail:</label>
                    <input type="email" id="email" name="email" required>
                </div>
                
                <div>
                    <label for="assunto">Assunto:</label>
                    <input type="text" id="assunto" name="assunto">
                </div>
                
                <div>
                    <label for="mensagem">Mensagem:</label>
                    <textarea id="mensagem" name="mensagem" rows="5" required></textarea>
                </div>
                
                <button type="submit">Enviar Mensagem</button>

            </form>
            
            <p style="margin-top: 20px;">Ou entre em contato diretamente: Telefone: (99) 9999-9999 | Email: contato@grupoalencarveloso.com.br</p>

        </section>

    </main>

</body>
</html>
