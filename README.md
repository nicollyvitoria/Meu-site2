<!DOCTYPE html>
cd /storage/emulated/0/Download/Meu-site2-main/Meu-site2-main
git init
git remote add origin https://github.com/nicollyvitoria/Meu-site2.git
git add index.html
git commit -m "Add index.html na raiz"
git push -u origin main
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Meu Site2
    no GitHub Pages</title>
  <style>
    body { font-family: sans-serif; background: #f0f0f0; text-align: center; padding: 2rem; }
    h1 { color: #336699; }
  </style>
  <script>
    function ola() { alert('Olá do GitHub Pages!'); }
  </script>
</head>
<body>
  <h1>Bem-vindo ao meu site!</h1>
  <p>Publicado com GitHub Pages 🚀</p>
  <button onclick="ola()">Clique em mim</button>
</body>
</html>
git init
git add .
git commit -m "Primeiro commit"
git branch -M main
git remote add origin https://github.com/seu-usuario/repositorio.git
git push -u origin main

