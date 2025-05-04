
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <title>Dublagem Automática</title>
    <link rel="stylesheet" href="/static/style.css">
</head>
<body>
    <h1>Dublagem Automática de Vídeo</h1>
    <form action="/upload" method="POST" enctype="multipart/form-data">
        <input type="file" name="video" accept="video/*" required>
        <button type="submit">Enviar vídeo</button>
    </form>
</body>
</html>
