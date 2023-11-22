<!-- index.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Site</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="tab" onclick="openTab('tab1')">Aba 1</div>
    <div class="tab" onclick="openTab('tab2')">Aba 2</div>

    <div id="tab1Content" class="tab-content">
        <p>Conteúdo da Aba 1</p>
        <img src="caminho/para/sua/imagem1.jpg" alt="Descrição da imagem 1">
    </div>

    <div id="tab2Content" class="tab-content">
        <p>Conteúdo da Aba 2</p>
        <img src="caminho/para/sua/imagem2.jpg" alt="Descrição da imagem 2">
    </div>

    <script src="script.js"></script>
</body>
</html>