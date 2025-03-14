<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Meus objetivos do ano</title>
</head>
<body>

</body>
</html>
@import url('https://fonts.googleapis.com/css2?family=Chakra+Petch:wght@400;700&display=swap');

:root {
    --cor-de-fundo: #1E1E1E;
    --verde: #6FFF57;
    --branco: #FFFFFF;
    --botao-ativo: #3A375E;
    --botao-inativo: rgba(58, 55, 94, 0.5);
    --texto-fundo: rgba(58, 55, 94, 0.3);
}

body {
    background-color: var(--cor-de-fundo);
    color: var(--branco);
    font-family: 'Chakra Petch', sans-serif;
}


.conteudo-principal {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    max-width: 1200px;
    width: 100%;
    margin: 0 auto;
}

.titulo-principal {
    text-align: left;
    width: 100%;
    font-size: 32px;
}

.titulo-principal span {
    color: var(--verde);
}

.botao {
    font-family: "Crakra Petch", sans-serif;
    background-color: var(--botao-inativo);
    color: var(--branco);
    display: flex;
    justify-content: center;
    padding: 1em;
    font-size: 18px;
    align-items: center;
    width: 100%;
    border-bottom: 4px solid var(--botao-ativo);
    border-left: 2px solid var(--botao-ativo);
    border-right: 2px solid var(--botao-ativo);
    border-top: none;
}

.botao:first-child {
    border-radius: 40px 40px 0 0;
}

.botoes {
    display: block;
}/* código escondido */

@media screen and (min-width: 768px){
    .botoes{
        display:flex;
    }
}/* código escondido */

@media screen and (min-width: 768px){
    .botoes{
        display:flex;
    }
    .botao:first-child {
    border-radius: 40px 0 0 0;
    }
}/* código escondido */

@media screen and (min-width: 768px){
    .botoes{
        display:flex;
    }
    .botao:first-child {
        border-radius: 40px 0 0 0;
    }
    .botao:last-child {
        border-radius: 0 40px 0 0;
    }
}<!DOCTYPE html>
<html lang="pt-br">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Meus objetivos do ano</title>
    <link rel="stylesheet" href="style.css" />
  </head>

  <body>
    <section class="conteudo-principal">
      <h2 class="titulo-principal">Meus Objetivos do ano<span>_</span></h2>
      <div class="botoes">
        <button class="botao">Cursos na Alura</button>
        <button class="botao">Criar projetos em Javascript</button>
        <button class="botao">Criar um portfolio</button>
        <button class="botao">Atualizar meu currículo</button>
      </div>
    </section>
  </body>
</html>
@import url("https://fonts.googleapis.com/css2?family=Chakra+Petch:wght@400;700&display=swap");

:root {
  --cor-de-fundo: #1e1e1e;
  --verde: #6fff57;
  --branco: #ffffff;
  --botao-ativo: #3a375e;
  --botao-inativo: rgba(58, 55, 94, 0.5);
  --texto-fundo: rgba(58, 55, 94, 0.3);
}

body {
  background-color: var(--cor-de-fundo);
  color: var(--branco);
  font-family: "Chakra Petch", sans-serif;
}

.conteudo-principal {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  max-width: 1200px;
  width: 100%;
  margin: 0 auto;
}

.titulo-principal {
  text-align: left;
  width: 100%;
  font-size: 32px;
}

.titulo-principal span {
  color: var(--verde);
}

.botao {
  font-family: "Crakra Petch", sans-serif;
  background-color: var(--botao-inativo);
  color: var(--branco);
  display: flex;
  justify-content: center;
  padding: 1em;
  font-size: 18px;
  align-items: center;
  width: 100%;
  border-bottom: 4px solid var(--botao-ativo);
  border-left: 2px solid var(--botao-ativo);
  border-right: 2px solid var(--botao-ativo);
  border-top: none;
}

.botao:first-child {
  border-radius: 40px 40px 0 0;
}

.botoes {
  display: block;
}@media screen and (min-width: 768px) {
}@media screen and (min-width: 768px) {
  .botoes {
    display: flex;
  }
}@media screen and (min-width: 768px) {
  /* Código omitido */

  .botao:first-child {
    border-radius: 40px 0 0 0;
  }
}@media screen and (min-width: 768px) {
  /* Código omitido */

  .botao:last-child {
    border-radius: 0 40px 0 0;
  }
}.ativo {
  background-color: var(--botao-ativo);
  border-bottom: 4px solid var(--verde);
}<button class="botao ativo">Cursos na Alura</button>
<button class="botao">Criar projetos em Javascript</button>
<button class="botao">Criar um portfolio</button>
<button class="botao">Atualizar meu currículo</button>
<script src="main.js"></script>
const botoes = document.querySelectorAll(".botao");
console.log(botoes);