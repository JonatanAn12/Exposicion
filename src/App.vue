<template>
  <section id="inicio">
    <div class="contenido">
        <header>
          <div class="contenido-header">
            <div class="formas">
            <i class="fa-brands fa-bootstrap"></i>
          </div>
                <h1>Bootstrap</h1>
                <div class="container">
                <p>Presentado por: Jonatan Andres Sanchez Ayala</p>
                <p>Nikoll Valentina Melo Triana </p>
              </div>    
                <div class="collapse" id="navbarToggleExternalContent" data-bs-theme="dark">
                    <div class="bg-dark p-4">
                      <span class="text-body-secondary">
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
                          <h3 class="offcanvas-title" id="offcanvasNavbarLabel" type="bienvenida">Contenido</h3>
                          <button type="button" class="btn-close" data-bs-dismiss="offcanvas" aria-label="Close"></button>
                        </div>
                        <div class="offcanvas-body">
                          <ul class="navbar-nav justify-content-end flex-grow-1 pe-3">
                            <button>
                              <li class="nav-item">
                                <a class="nav-link active" aria-current="page" href="#inicio">INICIO</a>
                              </li>
                            </button>
                            <br>
                            <button>
                            <li class="nav-item">
                              <a class="nav-link active" aria-current="page" href="#contenido2">Tipografia en Bootstrapt</a>
                            </li>
                          </button>
                          <br>
                            <button>
                            <li class="nav-item">
                              <a class="nav-link" href="#">Alertas en Bootstrapt</a>
                            </li>
                          </button>
                          <br>
                         </ul>
                        </div>
                      </div>
                    </div>
                  </nav>
            </div>
        </header>
        <div class="presentacion">
            <p class="bienvenida">Bienvenidos</p>
            <h2>Hola esto es  <span>Bootstrap </span>Y les vamos a decir de que se trata esta libreria y su respectivo contenido.</h2>
            <p class="descripcion" >Nuestro grupo nos toco los siguentes contenidos, les hablaremos un poco de las alertas y las Tipografias
              de esta fabulosa libreria. sin antes contarles un poco sobre Bootstrap.</p>
              <div class="boots">
                <figure class="text-center">
                  <blockquote class="blockquote">
                <p class="h5"><u>Bootstrap es una popular Libreria de desarrollo web.</u> de código abierto que proporciona una colección de herramientas y estilos,
                   para la creación rápida y sencilla de sitios web y aplicaciones responsivas. Surgió en 2011 como un proyecto interno de Twitter.
                   inicialmente llamado "Twitter Blueprint" fue desarrollado por <strong>Mark Otto y Jacob Thornton</strong> de Twitter, con el objetivo de unificar la apariencia y la experiencia del usuario en sus diversas plataformas.
                    Posteriormente, fue lanzado como un proyecto de código abierto bajo el nombre de Bootstrap. Su popularidad creció rápidamente gracias a su facilidad de uso,
                     su amplia gama de componentes predefinidos y su capacidad de adaptarse a diferentes dispositivos y tamaños de pantalla. 
                     Desde entonces, ha sido ampliamente adoptado por desarrolladores web de todo el mundo y ha evolucionado con el tiempo para mantenerse al día con las tendencias y necesidades del diseño web moderno.</p>
                    </blockquote>
                     <figcaption class="blockquote-footer">
                      Desarrolladores: Mark Otto, Jacob Thornton y otros ingenieros de twitter
                    </figcaption>
                  </figure>
                    </div>
        </div>
    </div>
</section>
<section id="contenido2">
  <div class="contenido2">
      <p class="titulo-seccion">Typografic</p>
      <h2>Estas Son las <span>Typografic</span> de Bootstrap</h2>
      <h3>Headings</h3>
      <p>Bootstrap establece estilos básicos de visualización, tipografía y enlaces globales. Cuando se necesita más control, consulta las clases de utilidades textuales.

        Utiliza una pila de fuentes nativas que seleccione la mejor font-family para cada sistema operativo y dispositivo.
        Para una escala de tipos más inclusiva y accesible, utilizamos el font-size raíz predeterminado del navegador (normalmente 16x) para que los visitantes puedan personalizar los valores predeterminados de su navegador según sea necesario.
        Usa los atributos $font-family-base, $font-size-base y $line-height-base como nuestra base tipográfica aplicada al <strong>"body"</strong>
        Establece el color global de enlaces a través de $link-color.
        Usa $body-bg para establecer un background-color en "body" (#fff por defecto).
        Estos estilos se pueden encontrar dentro de _reboot.scss, y las variables globales se definen en _variables.scss. Asegúrate de configurar $font-size-base en rem.</p>
          
          <h6>A continuación le mostraremos ejemplos y usos</h6>

          <h1>h1. Bootstrap heading</h1>
          <h2>h2. Bootstrap heading</h2>
          <h3>h3. Bootstrap heading</h3>
          <h4>h4. Bootstrap heading</h4>
          <h5>h5. Bootstrap heading</h5>
          <h6>h6. Bootstrap heading</h6>
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
    box-sizing: border-box !important;
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
  font-size: 22px;
  text-transform: uppercase;
  color: #6e2cf3;
  text-decoration: underline;
  text-decoration-color: #d3d3d3;
  text-decoration-thickness: 5px;
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
.navbar-toggler-icon {
    background-color:  #6e2cf3;
}

#contenido2 {
  max-width: 1100px;
  margin: auto;
  padding: 100px 15px;
  color: #111135;
  display: flex;
}

#contenido2 .contenido2 {
  margin: 0 40px;
}

#contenido2 .contenido2 .titulo-seccion {
  font-size: 22px;
  text-transform: uppercase;
  color: #6e2cf3;
  text-decoration: underline;
  text-decoration-color: #d3d3d3;
  text-decoration-thickness: 5px;
}

#contenido2 .contenido2 h2 {
  font-size: 34px;
  font-weight: bold;
  margin: 20px 0;
  letter-spacing: 2px;
}

#contenido2 .contenido2 h2 span {
  color: #9800B7;
}

#contenido .contenido2 h3 {
  font-size: 18px;
  font-weight: 500;
  text-transform: uppercase;
  margin-bottom: 20px;
  letter-spacing: 1px;
}

#contenido2 .contenido2 p {
  font-size: 22px;
  line-height: 25px;
  color: #565656;
  margin-bottom: 12px;
}

.container {
  display: flex;
  flex-direction: column;
  align-items: center;
  font-size: 20px;
}

button {
  font-size: 20px;
  font-weight: bold;
  text-transform: uppercase;
  padding: 15px 30px;
  background-color: #6e2cf3;
  border: none;
  border-radius: 30px;
  cursor: pointer;
  overflow: hidden;
  box-shadow: 0 0 20px rgba(110, 44, 243);
  transition: box-shadow .5s
}

button:hover {
  box-shadow: 0 0 10px rgba(110, 44, 243); 
}

#inicio .contenido header .contenido-header nav ul li button {
  margin-right: 20px; 
}

#inicio .contenido header .contenido-header nav ul li button h3 {
  text-transform: uppercase;
  color: #6e2cf3;
  text-decoration: underline;
  text-decoration-color: #d3d3d3;
  text-decoration-thickness: 5px;
}

.formas {
  display: inline-block

}

.formas i {
  text-decoration: none;
    color: #fff;
    display: inline-block;
    padding: 10px;
    margin: 10px;
    font-size: 40px;
}

.navbar bg-purple fixed-top {
  margin-top: 1px;
}

</style>
