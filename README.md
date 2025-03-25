<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Área Protegida</title>
    <style>
        body { font-family: Arial, sans-serif; text-align: center; margin: 50px; background-color: #E3F2FD; color: #0D47A1; }
        #content { display: none; }
        .portfolio-section { margin-top: 20px; background: white; padding: 15px; border-radius: 10px; box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.1); }
        h2, h3 { color: #0D47A1; }
        ul { list-style-type: none; padding: 0; }
        li { background: #BBDEFB; padding: 8px; margin: 5px; border-radius: 5px; }
        button { background-color: #0D47A1; color: white; padding: 10px 15px; border: none; border-radius: 5px; cursor: pointer; }
        button:hover { background-color: #1565C0; }
    </style>
</head>
<body>
    <div id="login">
        <h2>Digite a senha para acessar o portfólio</h2>
        <input type="password" id="password" placeholder="Senha">
        <button onclick="checkPassword()">Entrar</button>
        <p id="error" style="color: red; display: none;">Senha incorreta!</p>
    </div>
    
    <div id="content">
        <h2>Guilherme Zavodski</h2>
        <div class="portfolio-section">
            <h3>Conheçendo o Guilherme</h3>
            <p>Sou um desenvolvedor apaixonado por tecnologia e inovação, nas horas vagas jogo vôlei.</p>
        </div>
        <div class="portfolio-section">
            <h3>Áreas do Conhecimento</h3>
            <ul>
                <li>HTML, CSS, JavaScript</li>
                <li>React, Flutter</li>
                <li>Desenvolvimento Web e Mobile</li>
            </ul>
        </div>
        <div class="portfolio-section">
            <h3>Projetos</h3>
            <ul>
                <li><strong>Projeto 1:</strong> Site de uma Plataforma de Cursos e Formações Online</li>
                <li><strong>Projeto 2:</strong> Aplicativo mobile para Atletas</li>
                <li><strong>Projeto 3:</strong> Criação de Planilhas e Agendas usando Macro no Excel</li>
            </ul>
        </div>
    </div>
    
    <script>
        function checkPassword() {
            const password = document.getElementById("password").value;
            const correctPassword = "1234"; // Altere para a senha desejada
            
            if (password === correctPassword) {
                document.getElementById("login").style.display = "none";
                document.getElementById("content").style.display = "block";
            } else {
                document.getElementById("error").style.display = "block";
            }
        }
    </script>
</body>
</html>

    <script>
        function checkPassword() {
            const password = document.getElementById("password").value;
            const correctPassword = "1234"; // Altere para a senha desejada
            
            if (password === correctPassword) {
                document.getElementById("login").style.display = "none";
                document.getElementById("content").style.display = "block";
            } else {
                document.getElementById("error").style.display = "block";
            }
        }
    </script>
</body>
</html>
