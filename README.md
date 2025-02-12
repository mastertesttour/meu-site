<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Site Grátis</title>
    <style>
        body { font-family: Arial, sans-serif; text-align: center; background-color: #f4f4f4; padding: 20px; }
        .container { max-width: 800px; margin: auto; background: white; padding: 20px; border-radius: 8px; box-shadow: 0 0 10px rgba(0,0,0,0.1); }
        img { max-width: 100%; border-radius: 8px; }
        video { width: 100%; border-radius: 8px; }
        input, textarea, button { width: 100%; padding: 10px; margin: 5px 0; }
    </style>
</head>
<body>
    <div class="container">
        <h1>Bem-vindo ao Meu Site</h1>
        <p>Esse é um site gratuito hospedado no GitHub Pages.</p>
        
        <h2>📸 Minha Foto</h2>
        <img src="https://via.placeholder.com/600x300" alt="Minha Imagem">

        <h2>🎥 Meu Vídeo</h2>
        <video controls>
            <source src="https://www.w3schools.com/html/mov_bbb.mp4" type="video/mp4">
            Seu navegador não suporta vídeos.
        </video>

        <h2>📩 Envie uma Mensagem</h2>
        <form action="https://formspree.io/f/{seu-email}" method="POST">
            <input type="text" name="name" placeholder="Seu Nome" required>
            <input type="email" name="_replyto" placeholder="Seu Email" required>
            <textarea name="message" placeholder="Sua Mensagem" required></textarea>
            <button type="submit">Enviar</button>
        </form>
    </div>
</body>
</html>
# meu-site
