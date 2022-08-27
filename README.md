<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="shortcut icon" href="IMGs/ramen.png" type="image/x-icon">
    <link rel="stylesheet" href="style.css">
    <title>Portifólio</title>
</head> 
<body>

    <header>
        <nav class="menu">
            <ul>
                <li><a href="#inicio">Início</a></li>
                <li><a href="#my">Sobre mim</a></li>
                <li><a href="#form">Formação</a></li>
                <li><a href="#cursos">Cursos</a></li>
                <li><a href="#projeto">Projetos</a></li>
                <li><a href="#redes">Redes Sociais</a></li>
                <li class="night" onclick="light()"><a href="#">☀️</a></li>
            </ul>
        </nav>
    </header> 
    <hr>
    <main>
        <section id="inicio">
            <div id="light">
                <h2>| Início</h2>
                <p>Olá, meu nome é Marcelo, e nesse portifólio irei falar sobre as coisas q eu geralmente gosto e minhas formações. Também deixei algusn crusos básicos</p>
            </div>
            <div class="imgright">
                <img src="IMGs/science-removebg-preview.png" class="inicioimg">
            </div>
        </section>
        <hr>
        <section id="my">
            <div id="light2">
                <h2>| Sobre mim</h2>
                <p class="myp">&#128510 Otaku</p>
                <p class="myp">&#x1F3AE Gamer</p>
                <p class="myp">&#x1F4BB Programador Front-end</p>
                <p class="myp">&#x1F4D7 Estudante</p>
                <p class="myp">&#x1F9CA Cubista</p>
            </div>
            <div class="imgright">
                <img src="IMGs/individual-removebg-preview.png" class="myimg">
            </div>
        </section>
        
        <hr>
        <section id="form">
            <div id="light3">
                <h2>| Formação</h2>
                <p>&#x1F40D Python</p>
                <p>&#x1F310 Web</p>
                <p>&#x1F3B2 Banco de Dados</p>
                <p>&#x1F4CA Estatísticas</p>
                <p>&#x1F52C Data Science</p>
            </div>
            <div class="imgright">
                <img src="IMGs/em-formacao-removebg-preview.png" class="formimg">
            </div>
        </section>
        <hr>
        <section id="cursos">
            <div id="light4">
                <div id="curso">
                    <h2>| Cursos Disponíveis:</h2>
                </div>
                <div class="container" id="web">
                    <strong>
                        <p>WEB <br>
                            <img src="IMGs/set-di-icone-html5-css3-js-logo-di-sviluppo-web-insieme-di-icone-html-css-e-javascript-simbolo-di-programmazione-2fwhtnb.jpg" class="cursoimg">
                        </p>
                    </strong>
                </div>
                <div class="container" id="py">
                    <strong>
                        <p>Python <br>
                            <img src="IMGs/python.png" alt="python" class="cursoimg">
                        </p>
                    </strong>
                </div>
                <div class="container" id="c">
                    <strong>
                        <p>C <br>
                            <img src="IMGs/C_Logo.png" alt="C" class="cursoimg">
                        </p>
                    </strong>
                </div>
                <div class="container" id="sharp">
                    <strong>
                        <p>C# <br>
                            <img src="IMGs/c-sharp.png" alt="C#" class="cursoimg">
                        </p>
                    </strong>
                </div>
                <div class="container" id="lg">
                    <strong>
                        <p>Lógica de Programação <br>
                            <img src="IMGs/lg.jpg" class="cursoimg">
                        </p>
                    </strong>
                </div>
                <div class="container" id="sql">
                    <strong>
                        <p>SQL <br>
                            <img src="IMGs/database.png" class="cursoimg">
                        </p>
                    </strong>
                </div>
            </div>
        </section>
        <hr>
        <section id="projeto">
            <div id="light5" class="projeto">
                <h2 class="pro">| PROJETOS</h2>
                <div class="breve">
                    <div class="caixa">EM BREVE</div>
                    <div class="caixa">EM BREVE</div>
                    <div class="caixa">EM BREVE</div>
                    <div class="caixa">EM BREVE</div>
                    <div class="caixa">EM BREVE</div>
                    <div class="caixa">EM BREVE</div>
                    <div class="caixa">EM BREVE</div>
                </div>
            </div>
        </section>
    </main>
    <hr>
    <footer id="redes">
        <strong>
            <p style="color: white;">Me siga nas redes sociais</p>
        </strong>
        <img src="IMGs/instagram.png" alt="instagram" onclick="insta()" class="cursoimg">
        <img src="IMGs/facebook.png" alt="facebook" onclick="face()" class="cursoimg">
        <img src="IMGs/youtube.png" alt="youtube" onclick="yt()" class="cursoimg">
    </footer>
    <script src="funcoes.js"></script>
    <script src="script.js"></script>
</body>
</html>
