<template>
  <section id="inicio">
    <div class="contenido">
        <header>
          <div class="contenido-header">
            <div class="formas">
            <i class="fa-brands fa-bootstrap"></i>
          </div>
                <h1>Bootstrap</h1>
                <br>
                <div class="container">
                <p>Presentado por: Jonatan Andres Sanchez Ayala</p>
                <p>Nikoll Valentina Melo Triana </p>
              </div>    
                <div class="collapse" id="navbarToggleExternalContent" data-bs-theme="dark">
                    <div class="bg-dark p-2">
                      <span class="text-body-secondary">
                     </span>
                    </div>
                  </div>
                  <nav class="navbar bg-purple fixed-top" type="ligth" v-show="showNavbar">
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
                              <a class="nav-link" href="#contenidos3">Alertas en Bootstrapt</a>
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
        <button @click="toggleNavbar">Toggle Navbar</button>
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
    <div class="tituloa">
      <p class="titulo-seccion">Typografic</p>
      <h2>Estas Son las <span>Typografic</span> de Bootstrap</h2>
      <br>
      <p>Bootstrap establece estilos básicos de visualización, tipografía y enlaces globales. Cuando se necesita más control, consulta las clases de utilidades textuales.
        Utiliza una pila de fuentes nativas que seleccione la mejor font-family para cada sistema operativo y dispositivo.
        Para una escala de tipos más inclusiva y accesible, utilizamos el font-size raíz predeterminado del navegador (normalmente 16x) 
        para que los visitantes puedan personalizar los valores predeterminados de su navegador según sea necesario.
        Usa los atributos $font-family-base, $font-size-base y $line-height-base como nuestra base tipográfica aplicada al <strong>"body"</strong>
        Establece el color global de enlaces a través de $link-color.
        Usa $body-bg para establecer un background-color en <strong>"body"</strong> (#fff por defecto).
        Estos estilos se pueden encontrar dentro de _reboot.scss, y las variables globales se definen en _variables.scss. Asegúrate de configurar $font-size-base en rem.</p>
      </div>
        <br>
        <h6>A continuación le mostraremos ejemplos y usos</h6>
        <br>
            <u><h3>Mostrar encabezados</h3></u>
            <h1 class="display-1">Display 1</h1>
            <h1 class="display-2">Display 2</h1>
            <h1 class="display-3">Display 3</h1>
            <h1 class="display-4">Display 4</h1>
            <h1 class="display-5">Display 5</h1>
            <h1 class="display-6">Display 6</h1>
  <br>
          <u><h3>Encabezados</h3></u>
          <p class="h1">h1. Bootstrap heading</p>
          <p class="h2">h2. Bootstrap heading</p>
          <p class="h3">h3. Bootstrap heading</p>
          <p class="h4">h4. Bootstrap heading</p>
          <p class="h5">h5. Bootstrap heading</p>
          <p class="h6">h6. Bootstrap heading</p>
          <p>You can use the mark tag to <mark>highlight</mark> text.</p>
          <br>
          <u><h3>Elementos de texto en linea</h3></u>
          <br>
          <p><del>This line of text is meant to be treated as deleted text.</del></p>
          <p><s>This line of text is meant to be treated as no longer accurate.</s></p>
          <p><ins>This line of text is meant to be treated as an addition to the document.</ins></p>
          <p><u>This line of text will render as underlined</u></p>
          <p><small>This line of text is meant to be treated as fine print.</small></p>
          <p><strong>This line rendered as bold text.</strong></p>
          <p><em>This line rendered as italicized text.</em></p>
        <br>
          <u><h3>Abreviaciones</h3></u>
          <p><abbr title="attribute">attr</abbr></p>
          <p><abbr title="HyperText Markup Language" class="initialism">HTML</abbr></p>
          <br>

          <u><h3>Blockquote o Citas en Bloque</h3></u>
          <br>
          <blockquote class="blockquote">
            <p class="mb-0">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.</p>
          </blockquote>

          <u><h3>Naming a source</h3></u>
          <br>
          <blockquote class="blockquote">
            <p class="mb-0">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.</p>
            <footer class="blockquote-footer">Someone famous in <cite title="Source Title">Source Title</cite></footer>
          </blockquote>
          <br>
          <u><h3>Naming a source</h3></u>
          <br>
          <blockquote class="blockquote text-center">
            <p class="mb-0">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.</p>
            <footer class="blockquote-footer">Someone famous in <cite title="Source Title">Source Title</cite></footer>
          </blockquote>
          <br>
          <u><h3>Listas</h3></u>
          <br>
          <ul class="list-unstyled">
            <li>Lorem ipsum dolor sit amet</li>
            <li>Consectetur adipiscing elit</li>
            <li>Integer molestie lorem at massa</li>
            <li>Facilisis in pretium nisl aliquet</li>
            <li>Nulla volutpat aliquam velit
              <ul>
                <li>Phasellus iaculis neque</li>
                <li>Purus sodales ultricies</li>
                <li>Vestibulum laoreet porttitor sem</li>
                <li>Ac tristique libero volutpat at</li>
              </ul>
            </li>
            <li>Faucibus porta lacus fringilla vel</li>
            <li>Aenean sit amet erat nunc</li>
            <li>Eget porttitor lorem</li>
          </ul>




  </div>
</section>
<section id="contenidos3">
  <div class="contenidos3">
    <div class="tituloa">
      <p class="titulo-seccion"> Alertas </p>
      <h2>Estas Son las <span><u>Alertas</u></span> de Bootstrap</h2>
      <h3>¿Qué es una alerta???</h3>
      <p>Se usa para advertir al usuario del navegador de que algo está mal o de que algo debería mejorar,
         así como para dar información sobre algo concreto, por ejemplo, que se debe introducir un texto en vez de un número.
         Las alertas en Bootstrap han estado disponibles prácticamente desde el inicio del proyecto, ya que son una característica 
         fundamental para proporcionar retroalimentación al usuario en aplicaciones web. Desde entonces, Bootstrap ha evolucionado constantemente 
         para mantenerse al día con las necesidades y tendencias del diseño web moderno. Las alertas han sido una parte integral de esta evolución 
         y se han mejorado y refinado en las diferentes versiones de Bootstrap.</p>
         <br>
      <p> Las alertas en Bootstrap son componentes muy útiles para mostrar mensajes informativos, advertencias, errores o éxito al usuario. 
        Estas alertas son altamente personalizables y vienen con diferentes estilos predefinidos que pueden adaptarse fácilmente al diseño de tu sitio web o aplicación..</p>
      </div>
      <br>
      <u><h3>estos son algunos ejemplos sobre las alarmas</h3></u>
      <br>
      <div class="alert alert-primary" role="alert">
        A simple primary alert—check it out!
      </div>
      <div class="alert alert-secondary" role="alert">
        A simple secondary alert—check it out!
      </div>
      <div class="alert alert-success" role="alert">
        A simple success alert—check it out!
      </div>
      <div class="alert alert-danger" role="alert">
        A simple danger alert—check it out!
      </div>
      <div class="alert alert-warning" role="alert">
        A simple warning alert—check it out!
      </div>
      <div class="alert alert-info" role="alert">
        A simple info alert—check it out!
      </div>
      <div class="alert alert-light" role="alert">
        A simple light alert—check it out!
      </div>
      <div class="alert alert-dark" role="alert">
        A simple dark alert—check it out!
      </div>
      <br>
      <u><h3>Alarmas con links</h3></u>
      <br>
      <div class="alert alert-primary" role="alert">
        A simple primary alert with <a href="#" class="alert-link">an example link</a>. Give it a click if you like.
      </div>
      <div class="alert alert-secondary" role="alert">
        A simple secondary alert with <a href="#" class="alert-link">an example link</a>. Give it a click if you like.
      </div>
      <div class="alert alert-success" role="alert">
        A simple success alert with <a href="#" class="alert-link">an example link</a>. Give it a click if you like.
      </div>
      <div class="alert alert-danger" role="alert">
        A simple danger alert with <a href="#" class="alert-link">an example link</a>. Give it a click if you like.
      </div>
      <div class="alert alert-warning" role="alert">
        A simple warning alert with <a href="#" class="alert-link">an example link</a>. Give it a click if you like.
      </div>
      <div class="alert alert-info" role="alert">
        A simple info alert with <a href="#" class="alert-link">an example link</a>. Give it a click if you like.
      </div>
      <div class="alert alert-light" role="alert">
        A simple light alert with <a href="#" class="alert-link">an example link</a>. Give it a click if you like.
      </div>
      <div class="alert alert-dark" role="alert">
        A simple dark alert with <a href="#" class="alert-link">an example link</a>. Give it a click if you like.
      </div>
      <br>
      <u><h3>Contenido Adicional</h3></u>
      <br>
      <div class="alert alert-success" role="alert">
        <h4 class="alert-heading">Well done!</h4>
        <p>Aww yeah, you successfully read this important alert message. This example text is going to run a bit longer so that you can see how spacing within an alert works with this kind of content.</p>
        <hr>
        <p class="mb-0">Whenever you need to, be sure to use margin utilities to keep things nice and tidy.</p>
      </div>
      <br>
      <u><h3>Despedir</h3></u>
      <br>
      <div class="alert alert-warning alert-dismissible fade show" role="alert">
        <strong>Holy guacamole!</strong> You should check in on some of those fields below.
        <button type="button" class="close" data-dismiss="alert" aria-label="Close">
          <span aria-hidden="true">&times;</span>
        </button>
      </div>
      
    </div>
  </section>
</template>

<script>
export default {
  data() {
    return {
      showNavbar: true 
    };
  },
  methods: {
    toggleNavbar() {
      this.showNavbar = !this.showNavbar;
    }
  }
};
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
  display: grid;
    background-color: #6e2cf3;
    position: fixed;
    width: 100%;
    height: 90px;
    z-index: 100;
    top: 0;
}

#inicio .contenido header .contenido-header {
    max-width: 1100px;
    margin: auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0 20px;
}


#inicio .contenido header button {
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
#inicio .contenido header button:hover {
  box-shadow: 0 0 10px rgba(110, 44, 243); 
  color: #fff;
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
#inicion .contenido  h3 {
  font-size: 22px;
  text-transform: uppercase;
  color: #6e2cf3;
  text-decoration: underline;
  text-decoration-color: #d3d3d3;
  text-decoration-thickness: 5px 
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

#inicio .contenido header .contenido-header nav ul li button {
  margin-right: 20px; 
}

#inicio .contenido header  h3 {
  text-transform: uppercase;
  color: #6e2cf3;
  text-decoration: underline;
  text-decoration-color: #d3d3d3;
  text-decoration-thickness: 5px;
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

#contenido2 .contenido2 span  h3 {
  font-size: 18px;
  font-weight: 500;
  text-transform: uppercase;
  margin-bottom: 20px;
  letter-spacing: 1px;
}

#contenido2 .contenido2 .tituloa p {
  font-size: 22px;
  line-height: 25px;
  color: #565656;
  margin-bottom: 15px;
}

.container {
  display: flex;
  margin: 0 30px;
  padding: 0  20px;
  justify-content: space-between;
  flex-direction: column;
  align-items: center;
  font-size: 20px;
}


.formas i {
  display: inline-block;
  text-decoration: none;
    color: #fff;
    display: inline-block;
    padding: 10px;
    margin: 10px;
    font-size: 40px;
}

.navbar-toggler-icon {
  background-color:  #6e2cf3;
  margin: 0;
}

#contenidos3 {
  max-width: 1100px;
  margin: auto;
  padding: 100px 15px;
  color: #111135;
  display: flex;
}

#contenidos3 .contenidos3 {
  margin: 0 40px;
}

#contenidos3 .contenidos3 .titulo-seccion {
  font-size: 22px;
  text-transform: uppercase;
  color: #6e2cf3;
  text-decoration: underline;
  text-decoration-color: #d3d3d3;
  text-decoration-thickness: 5px;
}

#contenidos3 .contenidos3 h2 {
  font-size: 34px;
  font-weight: bold;
  margin: 20px 0;
  letter-spacing: 2px;
}

#contenidos3 .contenidos3 h2 span {
  color: #9800B7;
}

#contenidos3 .contenidos3 h2 span h3 {
  font-size: 18px;
  font-weight: 500;
  text-transform: uppercase;
  margin-bottom: 20px;
  letter-spacing: 1px;
}

#contenidos3 .contenidos3 .tituloa p {
  font-size: 22px;
  line-height: 25px;
  color: #565656;
  margin-bottom: 15px;
}

.navbar-custom {
  height: 20px; 
}

@media (max-width: 768px) {
  .navbar-custom {
    height: 50px; 
  }
}





</style>

