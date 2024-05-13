<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8"> 
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portifolio</title>
    <link rel="stylesheet"  href="style.css">
</head>
  <body>
    <header></header>
    <main class="apresentacao">
        <section class="apresentacao__cont">
            <h1 class="apresentacao__cont__titulo">
            Eleve seu negócio digital a outro nível 
            <strong class="titulo_destaque">com um Front-end de qualidade!
            </strong></h1>
            <p class="apresentacao__cont__texto">Olá! Sou Joana Santos, desenvolvedora 
            Front-end com especialidade em <strong>React, HTML e
            CSS</strong>. Ajudo pequenos negócios e designers a 
            colocarem em prática boas ideias. Vamos 
            conversar?</p>
          <div class="apresentacao__links">
              <a class="apresentacao__links__link" href="https://instagram.com/rafaballerini">Instagram</a>
              <a class="apresentacao__links__link" href="https://github.com/guilhermeonrails">GitHub</a>
          </div>
        </section>
        <img src="imagem joana.png" alt="Foto da Joana Santos programando">
    </main>
    <footer></footer>
  </body>
</html>

---------------------------------------------------------------------------------------------------------------------------------

@import url('https://fonts.googleapis.com/css2?family=Krona+One&family=Montserrat:ital,wght@0,100..900;1,100..900&display=swap');
* {
    margin: 0;
    padding: 0;
}


body {
     height: 100vh;
     box-sizing: border-box;
     background-color: black;
     color: white;
}

.titulo_destaque { 
    color:aqua;
}

.apresentacao { 
    margin: 5% 20%;
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.apresentacao__cont {
    width: 615px;
    display: flex;
    flex-direction: column;
    gap: 40px;
}

.apresentacao__cont__titulo {
    font-size: 36px;
    font-family: "Krona One", sans-serif;
}

.apresentacao__cont__texto {
    font-size: 24px;
    font-family: "Montserrat", sans-serif;
}

.apresentacao__links {
    display: flex;
    justify-content: space-between;
}

.apresentacao__links__link {
    background-color: aqua;
    width: 280px;
    text-align: center;
    color:black;
    border-radius: 16px;
    margin: 20px;
    font-size: 24px;
    padding: 24.5px 0px;
    text-decoration: none;
    font-family: "Montserrat", sans-serif;
    font-weight: 600;
}
