<template>
  <section id="inicio">
    <div class="contenido">
        <header>
            <div class="contenido-header">
                <h1>Bootstrap</h1>
                <p>Presentado por: Jonatan Andres Sanchez Ayala</p>
                <br>
                                <p>Nikoll Valentina Melo Triana </p>    
                <div class="collapse" id="navbarToggleExternalContent" data-bs-theme="dark">
                    <div class="bg-dark p-4">
                      <h5 class="text-body-emphasis h4">Contenido</h5>
                      <span class="text-body-secondary">
                        <li><a href="#sobremi" onclick="seleccionar(this)">SOBRE MI</a></li>
                        <li><a href="#servicios" onclick="seleccionar(this)">SERVICIOS</a></li>
                        <li><a href="#portafolio" onclick="seleccionar(this)">PORTAFOLIO</a></li>
                        <li><a href="#contactos" onclick="seleccionar(this)">CONTACTOS</a></li>
                     </span>
                    </div>
                  </div>
                  <nav class="navbar bg-purple fixed-top" type="ligth">
                    <div class="container-fluid">
                      <button class="navbar-toggler" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasNavbar" aria-controls="offcanvasNavbar" aria-label="Toggle navigation">
                        <span class="navbar-toggler-icon"></span>
                      </button>
                      <div class="offcanvas offcanvas-end" tabindex="-1" id="offcanvasNavbar" aria-labelledby="offcanvasNavbarLabel">
                        <div class="offcanvas-header">
                          <h5 class="offcanvas-title" id="offcanvasNavbarLabel">Contenido</h5>
                          <button type="button" class="btn-close" data-bs-dismiss="offcanvas" aria-label="Close"></button>
                        </div>
                        <div class="offcanvas-body">
                          <ul class="navbar-nav justify-content-end flex-grow-1 pe-3">
                            <li class="nav-item">
                              <a class="nav-link active" aria-current="page" href="#">Tipografia en Bootstrapt</a>
                            </li>
                            <li class="nav-item">
                              <a class="nav-link" href="#">Alertas en Bootstrapt</a>
                            </li>
                            <li class="nav-item dropdown">
                              <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                                Dropdown
                              </a>
                              <ul class="dropdown-menu">
                                <li><a class="dropdown-item" href="#">Action</a></li>
                                <li><a class="dropdown-item" href="#">Another action</a></li>
                                <li>
                                  <hr class="dropdown-divider">
                                </li>
                                <li><a class="dropdown-item" href="#">Something else here</a></li>
                              </ul>
                            </li>
                          </ul>
                          <form class="d-flex mt-3" role="search">
                            <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
                            <button class="btn btn-outline-success" type="submit">Search</button>
                          </form>
                        </div>
                      </div>
                    </div>
                  </nav>
            </div>
        </header>
        <div class="presentacion">
            <p class="bienvenida">Bienvenidos</p>
            <h2>Hola esto es  <span>Bootstrap </span>Y les vamos a decir de que se trata esta libreria y su respectivo contenido.</h2>
            <p class="descripcion" >Soy un Joven apasioando por el tema de la programación. de manera que tanto me encanta
                saber del desarrollo de software, aprendo de manera rapida y eficaz, siempre quise estudiar este arte tan hermoso 
                y quiero conseguir grandes cosas a futuro.</p>
            <a href="#portafolio">Ir a Portafolio</a>
        </div>
    </div>
</section>
</template>

<script>
export default {

}
</script>

<style>
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Montserrat';
}

#inicio {
    background: linear-gradient(rgb(33, 37, 41), rgba(33, 37, 41,));
    background-size: cover;
    background-position: center center;
    height: 100vh;
}

#inicio .contenido header {
    background-color: #6e2cf3;
    position: fixed;
    width: 100%;
    z-index: 100;
    top: 0;
}

#inicio .contenido header .contenido-header {
    max-width: 1100px;
    margin: auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 10px 20px;
}

#inicio .contenido header .contenido-header h1 {
    text-align: center;
    color: #fff;
}

#inicio .contenido header .contenido-header nav ul {
    list-style: none;
    display: flex;
    align-items: center;
}

#inicio .contenido header .contenido-header nav ul li a {
    text-decoration: none;
    color: #212529;
    margin: 0 12px;
    font-weight: 400;
    transition: .5s;

}

#inicio .contenido header .contenido-header nav ul li a:hover {
    color: purple;
}

#inicio .contenido header .contenido-header .redes a {
    text-decoration: none;
    color: #6e2cf3;
    display: inline-block;
    margin-left: 10px;
    transition: .5s;
}

#inicio .contenido header .contenido-header .redes a:hover {
    color: #9800B7;
} 

#inicio .contenido header .contenido-header {
    color: #fff;
}

#inicio .contenido .presentacion {
    max-width: 1100px;
    height: 100vh;
    margin: auto;
    color: #212529;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}

#inicio .contenido .presentacion .bienvenida {
font-size: 16px;
margin-bottom: 20px;
text-transform: uppercase;
letter-spacing: 5px;
}

#inicion .contenido .presentacion h2 {
    font-size: 55px;
    margin-bottom: 25px;
    text-align: center;
}

#inicio .contenido .presentacion h2 span {
    font-size: 25px;
    color: purple
}

#inicio .contenido .presentacion .descripcion {
    max-width: 700px;
    margin: 25px auto;
    font-size: 18px;
    text-align: center;
}

#inicio .contenido .presentacion a {
    text-decoration: none;
    display: inline-block;
    margin: 25px;
    padding: 20px 25px;
    border: 2px solid #fff;
    border-radius: 50px;
    color: #ffff;
    font-weight: bold;
    text-transform: uppercase;
    transition: .5s;
}

#inicio .contenido .presentacion a:hover {
    background-color: #9800B7;
} 

.navbar-toggler-icon {
    background-color:  #6e2cf3;
}
</style>
