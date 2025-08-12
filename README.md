<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <title>Fórmula 1</title>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/bootstrap/5.3.3/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/bootstrap-icons/1.11.3/font/bootstrap-icons.min.css">
    <link rel="stylesheet" href="styles.css">
</head>

<body>
    <header class="p-5">

        <nav class="container d-flex justify-content-between align-items-center">
            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/6f/Formula_1_logo_2021.svg/800px-Formula_1_logo_2021.svg.png" class="nav-img" loading="lazy" alt="Logotipo da Fórmula 1">
            <ul class="nav mt-5">
                <li class="nav-item"><a class="nav-link" href="#inicio">Início</a></li>
                <li class="nav-item"><a class="nav-link" href="#galeria">Galeria</a></li>
                <li class="nav-item"><a class="nav-link" href="#contato">Contato</a></li>
            </ul>
            <div id="acessibilidade" class="menu-acessibilidade">
                <button id="botao-acessibilidade" class="btn btn-primary fw-bold rotacao-botao" aria-expanded="false">Acessibilidade</button>
                <div id="opcoes-acessibilidade" class="opcoes-acessibilidade apresenta-lista">
                    <button id="aumentar-fonte" class="btn btn-primary fw-bold" aria-label="Aumentar o tamanho da fonte">A+</button>
                    <button id="diminuir-fonte" class="btn btn-primary fw-bold" aria-label="Diminuir o tamanho da fonte">A-</button>
                    <button id="alterna-contraste" class="btn btn-primary fw-bold" aria-label="Alternar o contraste de cores"> <i class="bi bi-shadows"></i></button>
                </div>
            </div>
        </nav>

    </header>

    <main class="container my-5">

        <section id="inicio" class="my-5">
            <div class="inicio-fundo d-flex justify-content-between align-items-center">
                <div class="esquerda-conteudo">
                    <h1 class="display-4 text-white fst-italic fw-bold">Bem-vindo ao Mundo da</h1>
                    <img src="https://upload.wikimedia.org/wikipedia/commons/9/9e/Mercedes_F1_2020_W11_Car.jpg" class="mb-3" width="563" height="278" loading="lazy" alt="Carro da Mercedes na Fórmula 1">
                    <a href="#f1" class="btn btn-primary btn-lg botao-inicio fw-semibold">Quero saber mais!</a>
                </div>
                <img src="https://upload.wikimedia.org/wikipedia/commons/1/1c/Sebastian_Vettel_2018.jpg" alt="Imagem de Sebastian Vettel, piloto de Fórmula 1" title="Sebastian Vettel - Foto por Wikimedia Commons" class="img-fluid img-inicio">
            </div>
        </section>

        <section id="f1" class="my-5 pt-6 secao-f1" tabindex="0" aria-label="Seção explicativa sobre a Fórmula 1">
            <div class="container d-flex align-items-center ">
                <div class="col-4 d-flex justify-content-center ">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/8/87/F1_Cars_2020.jpg" class="rounded-pill" width="273" height="331" loading="lazy" alt="Carros de Fórmula 1 alinhados para uma corrida">
                </div>
                <div class="col-5">
                    <h2>O que é a Fórmula 1?</h2>
                    <p class="p-2">A Fórmula 1 é a principal categoria do automobilismo mundial, composta por competições anuais de corridas de carros. Considerada a competição mais rápida e prestigiosa do planeta, a Fórmula 1 atrai milhares de fãs ao redor do mundo, com eventos em diferentes países. Os carros utilizados são altamente tecnológicos, projetados para atingir velocidades superiores a 350 km/h.</p>
                </div>
            </div>
        </section>

        <section id="galeria" tabindex="0" aria-label="Seção de galeria de imagens">
            <h2 class="text-center pt-5">Galeria</h2>
            <div class="container p-3 mt-3 fundo-galeria ">

                <div class="row justify-content-md-center">
                    <div class="col-md-4">
                        <img src="https://upload.wikimedia.org/wikipedia/commons/1/16/Lewis_Hamilton_2019.jpg" class="img-fluid rounded-5" loading="lazy" alt="Lewis Hamilton durante uma corrida de Fórmula 1">
                    </div>
                    <div class="col-md-4">
                        <img src="https://upload.wikimedia.org/wikipedia/commons/6/69/Formula_1_2017_Season.jpg" class="img-fluid rounded-5" loading="lazy" alt="Carros de Fórmula 1 competindo em uma corrida">
                    </div>
                </div>
                <div class="row mt-4 justify-content-md-center">
                    <div class="col-md-4">
                        <img src="https://upload.wikimedia.org/wikipedia/commons/d/d1/Formula_1_cars_2020_Spain_GP.jpg" class="img-fluid rounded-5" loading="lazy" alt="Carros de Fórmula 1 em ação no GP da Espanha de 2020">
                    </div>
                    <div class="col-md-4">
                        <img src="https://upload.wikimedia.org/wikipedia/commons/5/56/2020_F1_Russian_GP_Paddock_2.jpg" class="img-fluid rounded-5" loading="lazy" alt="Paddock da Fórmula 1 durante o Grande Prêmio da Rússia 2020">
                    </div>
                </div>
            </div>
        </section>

        <section id="contato">
            <div class="container p-5 d-flex justify-content-center">
                <div class="col-md-8 col-lg-10 rounded-5 formulario">
                    <h2 class="mb-3">Entre em contato</h2>
                    <form>
                        <div class="form-group mb-3">
                            <label for="nome">Nome</label>
                            <input type="text" id="nome" name="nome" class="form-control rounded-3 mt-1" placeholder="Digite seu nome completo">
                        </div>
                        <div class="form-group mb-3">
                            <label for="email">Email</label>
                            <input type="email" id="email" name="email" class="form-control rounded-3 mt-1" placeholder="Digite seu email">
                        </div>
                        <div class="form-group mb-3">
                            <label for="mensagem">Mensagem</label>
                            <textarea id="mensagem" name="mensagem" class="form-control rounded-4 mt-2" rows="4" placeholder="Escreva sua mensagem"></textarea>
                        </div>
                        <div class="d-grid gap-2">
                            <button type="submit" class="btn btn-primary btn-lg rounded-pill">Enviar mensagem</button>
                        </div>
                    </form>
                </div>
            </div>
        </section>
    </main>

    <footer class="text-center p-3 fst-italic">
        <p>Acesse nossas redes:</p>
        <i class="bi bi-whatsapp"></i>
        <i class="bi bi-instagram"></i>
        <i class="bi bi-tiktok"></i>
        <p class="mt-3">Desenvolvido por Gustavo Galdino. Projeto fictício sem fins comerciais.</p>
    </footer>

    <script src="https://cdnjs.cloudflare.com/ajax/libs/scrollReveal.js/4.0.9/scrollreveal.js"></script>
    <script src="script.js"></script>

</body>

</html>
