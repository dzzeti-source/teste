<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login - Minha Aplicação</title>
    <link rel="stylesheet" href="styles.css"> <!-- Linka o arquivo CSS -->
</head>
<body>
    <div class="login-container">
        <form class="login-form">
            <h2>Acesse sua Conta</h2>
            <div class="input-group">
                <label for="email">E-mail</label>
                <input type="email" id="email" name="email" required placeholder="Digite seu e-mail">
            </div>
            <div class="input-group">
                <label for="password">Senha</label>
                <input type="password" id="password" name="password" required placeholder="Digite sua senha">
            </div>
            <button type="submit">Entrar</button>
            <div class="form-footer">
                <a href="#">Esqueci minha senha</a>
                <span>Não tem uma conta? <a href="#">Cadastre-se</a></span>
            </div>
        </form>
    </div>
</body>
</html>
