# AgenciaDEViagem.2
<!doctype html>
<html lang="pt">

<head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">

    <title>Site de Viagem.</title>
</head>

<body>
    <!--Menu com responsiva-->>
    <nav class="navbar col-12 position-fixed navbar-expand-lg navbar-dark bg-dark" style="z-index: 999">
        <div class="container-fluid col-11 m-auto">
            <a class="navbar-brand" href="#">INFINITO</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
                data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false"
                aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                    <li class="nav-item">
                        <a class="nav-link active" aria-current="page" href="#">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#destino">Destino</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Passagens</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#guia">Guia Turistico</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#hospedagem">Hospedagem</a>
                    </li>
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button"
                            data-bs-toggle="dropdown" aria-expanded="false">
                            Contato
                        </a>
                        <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                            <li><a class="dropdown-item" href="#">Quem somos</a></li>
                            <li>
                                <hr class="dropdown-divider">
                            </li>
                            <li><a class="dropdown-item" href="#">Fale conosco</a></li>
                        </ul>
                    </li>
                </ul>
                <form class="d-flex">
                    <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
                    <button class="btn btn-outline-success" type="submit">Procurar</button>
                </form>
            </div>
        </div>
    </nav>
    <br><br><br><br>

    <!--Carrocel-->

    <div id="carouselExampleIndicators" class="carousel slide" data-bs-ride="carousel">
        <div class="carousel-indicators">
            <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active"
                aria-current="true" aria-label="Slide 1"></button>
            <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1"
                aria-label="Slide 2"></button>
            <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2"
                aria-label="Slide 3"></button>
            <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="3"
                aria-label="Slide 4"></button>
        </div>
        <div class="carousel-inner">
            <div class="carousel-item active">
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/41/Porto_de_Galinhas-003.jpg/1200px-Porto_de_Galinhas-003.jpg"
                    style="padding:20px width: 100px; height: 600px;" class="d-block w-100" alt="Porto de Galinhas">
            </div>
            <div class="carousel-item">
                <img src="https://www.melhoresdestinos.com.br/wp-content/uploads/2019/02/passagens-aereas-paris-capa2019-02.jpg"
                    style="padding:20px width: 100px; height: 600px;" class="d-block w-100" alt="Paris">
            </div>
            <div class="carousel-item">
                <img src="https://letouristeblog.com/wp-content/uploads/2015/08/capa-len%C3%A7ois.jpg"
                    style="padding:20px width: 100px; height: 600px;" class="d-block w-100" alt="Lencois">
            </div>
            <div class="carousel-item">
                <img src="https://monarchairgroup.ru/wp-content/uploads/2019/11/kappadokiya-arenda-chastnogo-samoleta-vozdushnyj-charter.jpg"
                    style="padding:20px width: 100px; height: 600px;" class="d-block w-100" alt="Turquia">
            </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators"
            data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators"
            data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
        </button>
    </div>
    <br>

    <h6 class="text-center">Somos um site de viagens e turismo que informa e inspira outras pessoas como nós.
        Divulgamos conteúdos e notícias para fazer nossos leitores viajarem cada vez mais, mostrando que viajar pode ser
        mais fácil.
        Aqui você fica por dentro de dicas de lugares, pontos turísticos, passagens aéreas em promoção, indicação de
        hotéis, agências de passeios,
        dicas gastronômicas e muitas outras sugestões para você aproveitar ainda mais sua próxima viagem.</h6>

    <!-- Destino -->
    <div id="destino" class="destino"></div><br>
    <br>
    <h4 class="text-center"> Qual será o seu destino?</h4><br>
    <div class="col-1 m-auto">
        <div class="dropdown">
            <button class="btn btn-secondary dropdown-toggle" type="button" id="destinoMenuButton2"
                data-bs-toggle="dropdown" aria-expanded="false">
                Nacional
            </button>
            <ul class="dropdown-menu dropdown-menu-dark" aria-labelledby="dropdownMenuButton2">
                <li><a class="dropdown-item active" href="#">Porto de Galinhas</a></li>
                <li><a class="dropdown-item" href="#">Lencois</a></li>
                <li><a class="dropdown-item" href="#">Bahia</a></li>
                <li><a class="dropdown-item" href="#">Alagoas</a></li>
            </ul>
        </div>
        <br>

        <!--Outro botao-->
        <div class="dropdown">
            <button class="btn btn-secondary dropdown-toggle" type="button" id="dropdownMenuButton2"
                data-bs-toggle="dropdown" aria-expanded="false">
                Internacional
            </button>
            <ul class="dropdown-menu dropdown-menu-dark" aria-labelledby="dropdownMenuButton2">
                <li><a class="dropdown-item active" href="#">Italia</a></li>
                <li><a class="dropdown-item" href="#">Paris</a></li>
                <li><a class="dropdown-item" href="#">Turquia</a></li>
                <li><a class="dropdown-item" href="#">Mexico</a></li>
            </ul>
        </div>
    </div>

    <br>
    <!-- Guia de Lugares-->
    <div id="guia" class="Guia"></div><br>

    <h5 class="text-center">Conheça nossos Guias Turisticos</h5>
    <div class="row row-cols-1 row-cols-md-3 g-4 col-11 a-auto container-fluid">
        <div class="col">
            <div class="card">
                <img src="https://f7j8i5n9.stackpathcdn.com/wp-content/uploads/2015/06/TorreEiffelemParis.jpg"
                    style="padding: 10px;" class="card-img-top" alt="Paris">
                <div class="card-body">
                    <h5 class="card-title">Card title</h5>
                    <p class="card-text">This is a longer card with supporting text below as a natural lead-in to
                        additional content. This content is a little bit longer.</p>
                    <a href="#" class="btn btn-primary">Guia Turistico</a>
                </div>
            </div>
        </div>
        <div class="col">
            <div class="card">
                <img src="https://www.penaestrada.blog.br/wp-content/uploads/2020/11/onde-ficar-em-porto-de-galinhas-06.jpg"
                    style="padding: 10px;" class="card-img-top" alt="Porto de galinhas">
                <div class="card-body">
                    <h5 class="card-title">Card title</h5>
                    <p class="card-text">This is a longer card with supporting text below as a natural lead-in to
                        additional content. This content is a little bit longer.</p>
                    <a href="#" class="btn btn-primary">Guia Turistico</a>
                </div>
            </div>
        </div>
        <div class="col">
            <div class="card">
                <img src="https://media.iatiseguros.com/wp-content/uploads/2018/06/04005617/que-hacer-en-turquia-3.jpg"
                    style="padding: 10px;" class="card-img-top" alt="Turquia">
                <div class="card-body">
                    <h5 class="card-title">Card title</h5>
                    <p class="card-text">This is a longer card with supporting text below as a natural lead-in to
                        additional content.</p>
                    <a href="#" class="btn btn-primary">Guia Turistico</a>
                </div>
            </div>
        </div>
    </div>
    <br>
    <!--Outra div de hospedagem-->
    <div id="hospedagem" class="hospedagem"></div><br>

    <h5 class="text-center">Conheça nossos Hoteis Credenciais</h5>
    <div class="row row-cols-1 row-cols-md-3 g-4 col-11 a-auto container-fluid mb-3 ">
        <div class="col">
            <div class="card">
                <img src="https://cf.bstatic.com/xdata/images/hotel/270x200/304092051.jpg?k=a558ff416219a8e5a1423103d1939a46430ba1b2c532542707ccccba9ce2224d&o="
                    style="padding: 10px;" class="card-img-top" alt="Paris">
                <div class="card-body">
                    <h5 class="card-title">Card title</h5>
                    <p class="card-text">This is a longer card with supporting text below as a natural lead-in to
                        additional content. This content is a little bit longer.</p>
                    <a href="#" class="btn btn-primary">Saiba Mais</a>
                </div>
            </div>
        </div>
        <div class="col">
            <div class="card">
                <img src="https://portalbarreirinhas.com.br/home/media/com_mtree/images/listings/m/619.jpg"
                    style="padding: 10px;" class="card-img-top" alt="Porto de galinhas">
                <div class="card-body">
                    <h5 class="card-title">Card title</h5>
                    <p class="card-text">This is a longer card with supporting text below as a natural lead-in to
                        additional content. This content is a little bit longer.</p>
                    <a href="#" class="btn btn-primary">Saiba Mais</a>
                </div>
            </div>
        </div>
        <div class="col">
            <div class="card">
                <img src="https://guiaviajarmelhor.com.br/wp-content/uploads/2017/11/hotel-carverna-capadocia-25.jpg"
                    style="padding: 10px;" class="card-img-top" alt="Turquia">
                <div class="card-body">
                    <h5 class="card-title">Hotel Gamiras</h5>
                    <p class="card-text">This is a longer card with supporting text below as a natural lead-in to
                        additional content. This content is a little bit longer.</p>
                    <a href="#" class="btn btn-primary">Saiba Mais</a>
                </div>
            </div>
        </div>
    </div>
    <br>
    <br>
    <!--Caixa de mensagem-->
    <div class="mb-3 container-fluid">
        <label for="exampleFormControlInput1" class="form-label">Email</label>
        <input type="email" class="form-control" id="exampleFormControlInput1" placeholder="name@example.com">
    </div>
    <div class="mb-3 container-fluid">
        <label for="exampleFormControlTextarea1" class="form-label">Deixe sua Mensagem</label>
        <textarea class="form-control" id="exampleFormControlTextarea1" rows="3"></textarea> <br>
        <button class="btn btn-outline-success" type="submit">Enviar</button>
        <br>
    </div>

    <!--Footer-->>
    <footer>
        <div class="container-fluid bg-dark p-3">
            <div class="row">
                <div class="col-sm-12 text-white text-center">
                    <p class="mb-0">Desenvolvido por Paloma Genaro Squad59
                    <p>
                </div>
            </div>
        </div>
    </footer>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p"
        crossorigin="anonymous"></script>
</body>

</html>
