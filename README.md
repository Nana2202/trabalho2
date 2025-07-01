# trabalho2
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Meu Site Pessoal</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="container">
    <h1>Olá, eu sou [Seu Nome]</h1>
    <p class="bio">Sou desenvolvedor web apaixonado por tecnologia, programação e café ☕.</p>
    <div class="links">
      <a href="https://github.com/seuusuario" target="_blank">GitHub</a>
      <a href="https://linkedin.com/in/seuusuario" target="_blank">LinkedIn</a>
    </div>
  </div>
  <script src="script.js"></script>
</body>
</html>
body {
  font-family: Arial, sans-serif;
  background-color: #f8f9fa;
  color: #333;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  margin: 0;
}

.container {
  text-align: center;
  padding: 2rem;
  border-radius: 15px;
  background-color: #fff;
  box-shadow: 0 0 15px rgba(0,0,0,0.1);
}

h1 {
  color: #007bff;
}

.bio {
  font-size: 1.2rem;
  margin: 1rem 0;
}

.links a {
  margin: 0 10px;
  text-decoration: none;
  color: #007bff;
  font-weight: bold;
}

.links a:hover {
  text-decoration: underline;
}
