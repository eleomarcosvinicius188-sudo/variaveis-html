# variaveis-html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="variaveis.css">
    <title>Document</title>
</head>
<body>
    
    <body>
        <div class="caixa">
            <h1> ola mundo</h1>
            <p>exemplo simples usando css root.</p>
            <button>clique aqui</button>
        </div>
    </body>
</body>
</html>


:root{
    --cor-primaria: #bf1fe3;
    --cor-secundaria: #f574e0;
    --cor-fundo: #f4f4f5;
    --cor-texto: #27272a;
    --cor-branca: #ffffff;

    --fonte-principal: Arial, sansserif;

    --borda-principal-radius: 10px;
    --sombra: 0 4px 10px rgba(0, 0 0, 0.1);


}

body{
    margin: 0;
    padding: 0;
    font-family:var(--fonte-principal);
    background-color: var(--cor-fundo);
    color: var(--cor-texto);

    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;

}

caixa{
    background-color: var(--cor-fundo);
    padding: 30px;
    border-radius: var(--borda-radius);
    box-shadow: var(--sombra);
    text-align: center;
    width: pointer;


}

h1{
    color: var(--cor-primaria);
    
}

button{
    background-color: var(--cor-primaria);
    color: #f4f4f5;
    border: none;
    padding:  10px 20px;
    border-radius: var(--borda-radius);
    cursor: pointer;

}
