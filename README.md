<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Tela de Login</title>
  <style>
/* Resetando margens e definindo a fonte para toda a página */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Poppins', 'Times New Roman', Times, serif;
}

/* Definindo o fundo da página com um gradiente e centralizando o conteúdo */
body {
  height: 100vh; /* Altura total da tela */
  background: linear-gradient(135deg, #fca4f7, #81dfff); /* Fundo em degradê */
  display: flex; /* Flexbox para centralizar */
  align-items: center; /* Alinha verticalmente */
  justify-content: center; /* Alinha horizontalmente */
}

/* Estilizando o container do login */
.login-container {
  background: #fff5f5; /* Fundo branco */
  padding: 40px 30px; /* Espaçamento interno */
  border-radius: 200px; /* Bordas arredondadas */
  box-shadow: 0px 10px 20px rgba(0, 0, 0, 0.438); /* Sombra ao redor */
  width: 300px; /* Largura fixa */
  text-align: center; /* Centraliza o texto */
}

/* Estilizando o título (Login) */
.login-container h2 {
  margin-bottom: 10px; /* Espaço abaixo do título */
  color: #f570ea; /* Cor do texto */
  text-shadow:1px 3px 4px #00000060;
  font-size:30px;
}
/* estilizar os campos de entrada */
.login-container input{
    width: 100%; /* ocupar toda a largura */
    padding: 10px 15px; /* espaco interno */
    margin: 10px 0; /* espaco entre os dois input */
    border: 1px solid #00000050; /* largura e cor das bordas */
    border-radius: 8px; /* deixar as bordas redondas */
    font-size: 14px; /* tamanho da fonte */
    background-color: #e0f0fd;
}
/* estilizando o botao */
.login-container button{
    width: 50%;
    padding: 7px;
    margin-top: 6px; /*distancia entre botao e input*/
    border: none; /* tirar a borda*/
    color: #f363f3; /* cor do texto*/
    background-color: #00000013;
    font-size: 16px; /*tamanho da fonte*/
    font-weight: bold; /*deixar em negrito*/
    border-radius: 100px; /*deixar redondo*/
    cursor: grab; /*mudar o cursor*/
    transition: background 0.3s;
}
/* colocando animacao do botao (transitiom) */
.login-container button:hover{
    background: #00000088;
}
/* estilizar o texto "esqueceu a senha?" */
.login-container p{
    margin-top: 15px; /*espaco de cima*/
    font-size: 15px; /* tamanho da fonte*/
    color: #0a36367e; 
}
  </style>
</head>
<body>

  <div class="login-container">
    <h2>Login</h2>
    <form>
      <input type="text" placeholder="Usuário" required>
      <div><input type="password" placeholder="Senha" required>
      <div><button type="submit">Entrar</button>
    </form>
    <p>Esqueceu a senha?</p>
  </div>

</body>
</html>
