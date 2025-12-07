# Prova-trimestral-
<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Página de Login com Menu</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: #f0f0f0;
            margin: 0;
            padding: 0;
        }

        header {
            background: #333;
            color: white;
            padding: 15px;
            text-align: center;
        }

        nav {
            background: #444;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 16px;
        }

        nav a:hover {
            text-decoration: underline;
        }

        .login-box {
            background: white;
            width: 300px;
            margin: 60px auto;
            padding: 25px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }

        .login-box h2 {
            text-align: center;
        }

        .login-box input {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border-radius: 5px;
            border: 1px solid #ccc;
        }

        .login-box button {
            width: 100%;
            padding: 10px;
            background: #333;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        .login-box button:hover {
            background: #555;
        }
    </style>
</head>
<body>
    <header>
        <h1>Bem-vindo</h1>
    </header>

    <nav>
        <a href="https://github.com/felixmanuelfilipe77/Web-site" target="_blank">Projeto Web-site</a>
        <a href="https://github.com/felixmanuelfilipe77/Felix-Tabela" target="_blank">Projeto Tabela</a>
        <a href="https://github.com/felixmanuelfilipe77/Pag" target="_blank">Projeto Pag</a>
    </nav>

    <div class="login-box">
        <h2>Login</h2>
        <form>
            <input type="text" placeholder="Nome de usuário" required />
            <input type="password" placeholder="Senha" required />
            <button type="submit">Entrar</button>
        </form>
    </div>
</body>
</html>
